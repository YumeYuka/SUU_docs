---
title: 路径对照
titleTemplate: 苏柚 Android
---

|变量|单用户|多用户|需要root|
|-|-|-|-|
|`{id}`|`0`|`<用户ID>`|仅多用户|
|`{storage}`|`/sdcard`|`/storage/emulated/{id}`|仅多用户|
|`{androidData}`|`{storage}/Android/data`|`{storage}/Android/data`|是|
|`{androidMedia}`|`{storage}/Android/media`|`{storage}/Android/media`|是|
|`{androidObb}`|`{storage}/Android/obb`|`{storage}/Android/obb`|是|
|`{userData}`|`/data/data`|`/data/user/{id}`|是|
|`{dataMedia}`|`/data/media/0`|`/data/media/{id}`|是|
