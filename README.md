# **Blue Archive Character**
##### 🔍蔚蓝档案中国大陆服务器所有角色档案，更新到当期日程笔记的预告
##### 🔍Blue Archive China Mainland server all character archives, updated to the current schedule notes
#### **❗❗注意：此项目只适用于中国大陆服务器，日服和国际服的信息不包含在内**
#### **❗❗Attention: This repository is only applicable to China Mainland server, Japan and Global server informations are not included**

------------
## 📁文件说明
|  文件名称 file name  |  说明 description |
| ----- | ------------ |
| `characters.json`  |  中文字段名文件 Chinese field name file |
|  `characters_en.json` |  英文字段名文件 English field name file |
|  `character.txt` |  文本 Text document（不会更新 No longer update） |

## 📄Json格式 | Json format
范例 Example：
```json
"1": {
    "name": "圣园 未花",
    "intro_link": "https://kivo.wiki/data/character/1",
    "avatar_url": "https://static.kivo.wiki/images/students/圣园未花/avatar.png",
    "学院": "崔尼蒂综合学院",
    "社团": "茶话会",
    "武器类型": "冲锋枪",
    "稀有度": "3",
    "攻击类型": "贯穿",
    "防御类型": "轻装甲",
    "站位": "前排",
    "职能定位": "输出",
    "限定": "是"
  },

```
英文范例 English Example：
```json
 "1": {
    "name": "圣园 未花",
    "intro_link": "https://kivo.wiki/data/character/1",
    "avatar_url": "https://static.kivo.wiki/images/students/圣园未花/avatar.png",
    "school": "崔尼蒂综合学院",
    "club": "茶话会",
    "weapon": "冲锋枪",
    "rarity": "3",
    "attack_type": "贯穿",
    "defense_type": "轻装甲",
    "position": "前排",
    "function": "输出",
    "limit": "是"
  },

```

## ✅功能特征 | Feature
- 含txt文件和json文件
  Including txt files and json files
- 分为中文字段和英文字段
  Divided into Chinese field and English field
- 包含该角色在[kivo.wiki](http://kivo.wiki "kivo.wiki")上的顺序、头像、中文姓名、学院、社团、武器类型、稀有度、攻击类型、防御类型、站位、职能定位、限定情况
  Include the order on [kivo.wiki](http://kivo.wiki "kivo.wiki"), avatar, Chinese name, school, club, weapon, rarity, attack type, defense type, position, functional position, and limit
  
## ❗注意事项 | Attention
- 所有值均为中文，只有字段名不同
All values are in Chinese, only field names have both Chinese and English
- 所有内容为我手动收集，难免有信息错误，如发现错误，请直接在issue进行反馈，谢谢
All content was collected manually by me, so there may be some wrong information. If any wrong informations are found, please provide feedback directly on the issue. Thank you
- 所有名字均采用中国大陆服务器译名
All names are translated from China Mainland server

## 🌐字段说明 | Description
- `武器类型` 指的是专武类型
 `weapon` is exclusive weapon
- `站位` 指的是该角色在游戏当中的位置，有前排、中排、后排、SPECIAL（辅助）四个变量
 `position` refers to the position of the character in the game, with four variables: front row, middle row, back row, and SPECIAL
- `限定`指的是所有无法直接在卡池里抽取的角色都叫限定，包括特殊活动赠送角色
- `Limit` refers to all characters that cannot be directly extracted, including special event bonus characters

## ❇️资料来源与致谢 | Source & thanks
- 角色链接与头像：[kivo.wiki](http://kivo.wiki "kivo.wiki")
Character link and avatar: [kivo.wiki](http://kivo.wiki "kivo.wiki")

## 🏛️ 其他信息 | Others
- 文章 context：https://071400.xyz/2025/06/ba-character/
- BiliBili：https://space.bilibili.com/515626972
- Youtube：https://www.youtube.com/@tkttn0714

## 🖐️使用权限 | Usage permission
- 本仓库使用MIT License，你可以：修改、分发、商用，但需保留原始版权声明和许可条款
This repository uses the MIT License, which allows you to modify, distribute, and use it for commercial purposes, but you must retain the original copyright statement and license terms
