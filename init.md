<!--
# [rights]  Copyright 2022 brianddk at github https://github.com/brianddk
# [license] Apache 2.0 License https://www.apache.org/licenses/LICENSE-2.0
# [repo]    github.com/brianddk/trezor-sd
# [btc]     BTC-b32: bc1qwc2203uym96u0nmq04pcgqfs9ldqz9l3mz8fpj
# [tipjar]  github.com/brianddk/reddit/blob/master/tipjar/tipjar.txt
-->

# Notes

1.  Make branch on github
2.  CD to local directory
3.  `git init`
4.  Update Readme and License
5.  `git remote add origin gh.brianddk:brianddk/trezor-sd.git` (funny ssh config)
6.  `git fetch --all`
7.  `git checkout --track origin/main`
8.  Create a gist
9.  `git submodule add --name "vbox-usb" https://gist.github.com/ba7e80612889ad8368e227a5866a6164.git "gist/vbox-usb"`
10. Copy over settings from established `.git\config` to `.git\config` (funnify gist url)
11. Copy over settings to `.git\modules\vbox-usb\config` (funnify gist url)
12. `git add -A .`
13. `git commit -m "Initial commit from host"`
14. `git push`
