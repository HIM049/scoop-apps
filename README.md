<p align="center">
  scoop-apps
</p>
<p align="center">
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub" src="https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square&color=f83500"/></a>
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/kkzzhizhou/scoop-apps?style=flat-square"/></a>
  <a href="https://github.com/kkzzhizhou"><img alt="GitHub user" src="https://img.shields.io/badge/author-kkzzhizhou-brightgreen?style=flat-square"/></a>
</p>


## 介绍

此仓库每天自动合并其他scoop仓库的更新

注意：如果仓库描述文件过时或者安装等问题，请根据仓库根路径的app-contributor-list.csv到相应的仓库提交issues

## 特性

- 每天更新
- 仓库列表根据项目[scoop-directory](https://github.com/rasa/scoop-directory)动态生成
- 自动处理同名文件，并优先采用较新版本, 重名文件以"软件-贡献人ID"重命名
- 自动去重（基于md5)
- json格式检验
- 支持仓库推荐、不推荐列表

## 说明

- 可接受仓库推荐，提交pr至bucket-recommend.txt即可
- 可接受"不维护仓库清理”，需在pr中说明理由，提交pr至bucket-not-recommend.txt即可
- **未对仓库软件来源进行安全检验，请自行甄别恶意软件，或者使用杀毒软件**
- 如果有软件安装问题，请参考仓库根路径的app-contributor-list.csv到相应的仓库提交issues

## 使用方法

```
scoop bucket add apps https://github.com/kkzzhizhou/scoop-apps
```

### 安装部分软件Hash Check Failed



因描述文件更新有概率更新到错误的文件，所以安装时出现“Hash Check Failed”，可以使用`-s`忽略，比如`scoop install xxx -s`即可，不放心的话可以到官网校验，或者根据仓库根路径的app-contributor-list.csv到相应的仓库提交issues

## 感谢

- [scoop-directory](https://github.com/rasa/scoop-directory)

## 合并仓库列表

- kkzzhizhou/scoop-zapps
- HCLonely/my-scoop-bucket
- Weidows-projects/scoop-3rd
- Sliots/scoop-bucket
- SayCV/scoop-cvp
- ScoopInstaller/PHP
- ScoopInstaller/Extras
- chawyehsu/dorado
- matthewjberger/scoop-nerd-fonts
- ivaquero/scoopet
- Calinou/scoop-games
- ScoopInstaller/Java
- TheRandomLabs/Scoop-Spotify
- borger/scoop-galaxy-integrations
- ScoopInstaller/Versions
- TheCjw/scoop-retools
- TheRandomLabs/scoop-nonportable
- kodybrown/scoop-nirsoft
- littleli/scoop-clojure
- kkzzhizhou/scoop-zapps
- rasa/scoops
- ScoopInstaller/Nirsoft
- kidonng/sushi
- scoopcn/scoopcn
- hoilc/scoop-lemon
- KNOXDEV/wsl
- Paxxs/Cluttered-bucket
- echoiron/echo-scoop
- ACooper81/scoop-apps
- ScoopInstaller/Nonportable
- hermanjustnu/scoop-emulators
- cderv/r-bucket
- couleur-tweak-tips/utils
- everyx/scoop-bucket
- dodorz/scoop
- borger/scoop-emulators
- Qv2ray/mochi
- TheRandomLabs/Scoop-Bucket
- ZvonimirSun/scoop-iszy
- kiennq/scoop-misc
- wangzq/scoop-bucket
- akirco/aki-apps
- ViCrack/scoop-bucket
- zhoujin7/tomato
- wzv5/ScoopBucket
- TheRandomLabs/Scoop-Python
- niheaven/scoop-sysinternals
- charmbracelet/scoop-bucket
- naderi/scoop-bucket
- amorphobia/siku
- jonz94/scoop-sarasa-nerd-fonts
- DoveBoy/Apps
- iquiw/scoop-bucket
- ygguorun/scoop-bucket
- NyaMisty/scoop_bucket_misty
- 42wim/scoop-bucket
- hu3rror/scoop-muggle
- jfut/scoop-jfut
- batkiz/backit
- mogeko/scoop-sysinternals
- ChungZH/peach
- aoisummer/scoop-bucket
- AStupidBear/scoop-bear
- starise/Scoop-Gaming
- Velgus/Scoop-Portapps
- aliesbelik/poldi
- starise/Scoop-Confetti
- Weidows-projects/scoop-3rd
- cc713/ownscoop
- seumsc/scoop-seu
- rivy/scoop-bucket
- Darkatse/Scoop-Darkatse
- brian6932/dank-scoop
- SayCV/scoop-cvp
- littleli/Scoop-littleli
- ChinLong/scoop-customize
- yuusakuri/scoop-bucket
- Darkatse/Scoop-KanColle
- AkariiinMKII/Scoop4kariiin
- mo-san/scoop-bucket
- babo4d/scoop-xrtools
- FlawlessCasual17/MyScoop
- MCOfficer/scoop-bucket
- KnotUntied/scoop-fonts
- beerpiss/scoop-bucket
- HUMORCE/nuke
- hulucc/bucket
- jingyu9575/scoop-jingyu9575
