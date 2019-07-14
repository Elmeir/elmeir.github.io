### ACT Plugin 5.0

Plugin | URL | Remark
------------ | ------------- | -------------
ACT | [https://advancedcombattracker.com/download.php](https://advancedcombattracker.com/download.php)
Parsing | [https://github.com/ravahn/FFXIV_ACT_Plugin](https://github.com/ravahn/FFXIV_ACT_Plugin)
Overlay | [https://github.com/hibiyasleep/OverlayPlugin](https://github.com/hibiyasleep/OverlayPlugin)
Hojoring| [https://github.com/anoyetta/ACT.Hojoring](https://github.com/anoyetta/ACT.Hojoring)
Triggernometry | [https://github.com/paissaheavyindustries/Triggernometry](https://github.com/paissaheavyindustries/Triggernometry)
ACTWebSocket | [https://github.com/ZCube/ACTWebSocket](https://github.com/ZCube/ACTWebSocket)
Cactbot | [https://github.com/quisquous/cactbot](https://github.com/quisquous/cactbot)
Kagami | [https://github.com/anoyetta-academy/kagami](https://github.com/anoyetta-academy/kagami)
Discord Triggers | [https://github.com/Makar8000/ACT-Discord-Triggers](https://github.com/Makar8000/ACT-Discord-Triggers)

### Overlay

Overlay | URL | Remark
------------ | ------------- | -------------
kagerou | `https://hibiyasleep.github.io/kagerou/overlay/`
mopimopi | `https://actzh.gitee.io/mopimopi/`
horiz | `https://bsides.github.io/horizoverlay/#/`
Ikegami | `https://idyllshi.re/ikegami/`
SkillDisplay | `https://rawrington.github.io/SkillDisplay/` | WebSocket

### Trigger

#### raid buff

Action | Reg | Recast
------------ | ------------- | -------------
Trick Attack/だまし討ち/攻其不备 | `15:.*:(?<name>.*):8D2:` | 60
Brotherhood/桃園結義/义结金兰 | `16:.*:(?<name>.*):1CE4:` | 90
Chain Stratagem/連環計/连环计 | `15:.*:(?<name>.*):1D0C:` | 120
Embolden/エンボルデン/鼓励 | `16:.*:(?<name>.*):1D60:` | 120
Dragon Sight/ドラゴンサイト/巨龙视线 | `15:.*:(?<name>.*):1CE6:` | 120
Technical Step/テクニカルステップ | `16:.*:(?<name>.*):3F4(1|2|3|4):` | 120
Divination/ディヴィネーション | `16:.*:(?<name>.*):40A8:` |  180
Battle Voice/バトルボイス/战斗之声 | `16:.*:(?<name>.*):76:` | 180
Battle Litany/バトルリタニー/战斗连祷  | `16:.*:(?<name>.*):DE5:` | 180
Aetherpact/エーテルパクト/以太契约 | `15:.*:(?<name>.*):1CFF:` | 180

#### others

Action | Reg | Recast
------------ | ------------- | -------------
Swiftcast/迅速魔/即刻咏唱 | `15:.*:(?<name>.*):1D89:` | 60


![Image](src)