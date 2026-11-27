# Bank C0 - Field
|From|To|Type|Content
|----|----|----|---
|$E500|$E5FF|Text|Key Items
|$F987|$FA9C|Pointers|Menu Texts (2 bytes * 139 items)
|$FA9D|$FE89|Text|Menu Texts (139 items)

# Bank C7 to CB - Dialogs
|From|To|Type|Content
|----|----|----|---
|C8/2220|C8/331F|Pointers|Speech (2 bytes * 2160 items)
|CA/0000|CA/FFFF|Text|Speech

# Bank D0 - Field & Battle Data
|From|To|Type|Content
|----|----|----|---
|$5C00|$67FF|Text|Monster Names (8 bytes * 384 items)
|$7000|$71FF|Pointers|Location Names (2 bytes * 164 items)
|$7200|$77FF|Text|Location Names
|$DEFA|$DF43|Text|Mr. Clio's Unknown Cave
|$E340|$E41A|Text|Crystal Prophecy
|$F000|$F1D3|Pointers|Battle Speech (2 bytes * 234 items)
|$F1D4|$FEBB|Text|Battle Speech (234 items)

# Bank D1 - Menu Data
|From|To|Type|Content
|----|----|----|---
|$1380|$1C7F|Text|Item Names (9 bytes * 256 items)
|$1C80|$1E2F|Text|Magic Names (6 bytes * 72 items)
|$1E30|$1E89|Text|Summon Names (6 bytes * 15 items)
|$1E8A|$247A|Text|Attack Names (9 bytes * 161 items)
|$28B6|$2975|Text|Status Names (8 bytes * 24 items)
|$2D00|$2D3F|Text|Shop Names (8 bytes * 8 items)
|$39A9|$3BA8|Pointers|Battle Messages
|$3BA9|$3F0D|Text|Battle Messages (256 items)
|$4000|$40FF|Pointers|Item Descriptions (2 bytes * 256 items)
|$4100|$41FF|Text|Item Descriptions (+Empty Space)
|$5500|$551D|Text|Character Names (6 bytes * 5 items)
|$5600|$56AF|Text|Job Names (8 bytes * 22 items)
|$5800|$59DF|Text|Battle Command Names (5 bytes * 96 items)
|$6200|$6307|Text|Innate Abilities Names (8 bytes * 33 items)
|$6700|$6AB0|Text|Special Abilities Names (9 bytes * 105 items)
|$7140|$7249|Pointers|Job/Ability Descriptions
|$724A|$7F9F|Text|Job/Ability Descriptions