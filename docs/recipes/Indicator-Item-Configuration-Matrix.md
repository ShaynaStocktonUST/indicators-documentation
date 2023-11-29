# Text Field
## Simple Setup
|Icon or Image|Empty Static Text Behavior|Zero Value Handling|Static Text|Field Value|Display Result|Status|
|---------|-----|------|-------|------|-----|-----|
|`standard:account`|`Use Field Value`|_any_||`Text`|Account Icon color with `TEX`|
|`standard:account`|`Use Field Value`|_any_||`0`|Account Icon color with `0`|Zero Value Handling only works with Number, Pct, Currency fields|
|`standard:account`|_any_|_any_|`ABC`|`Text`|Account Icon color with `ABC`|
|`standard:account`|`Use Icon Only`|_any_||`Text`|Account Icon|
|`standard:account`|_any_|_any_|_any_|[Blank]|No Icon|
|`standard:account`|_any_|_any_|`ABC`|`Text`|Account Icon color with `ABC`|
|`standard:account`|`Use Icon Only`|_any_||`Text`|Account Icon|
|`standard:account`|_any_|_any_|_any_|[Blank]|No Icon|
|`/img/samples/color_green.gif`|`Use Icon Only`|||`Text`|Green Square|Issue #91|
|`/img/samples/color_green.gif`|_any_||`ABC`|`Text`|Ghost Text|Not Recommended|
|`/img/samples/color_green.gif`|`Use Field Value`|||`Text`|Ghost Text|Not Recommended|
|`/img/samples/color_green.gif`|_any_|_any_|_any_|[Blank]|No Icon|

## Inverse Setup
`Show when False or Blank` is `true`
|Inverse Icon Value or Image|Empty Static Text Behavior|Zero Value Handling|Inverse Static Text|Field Value|Display Result|Status|
|---------|-----|------|------|-----|-----|-----|
|`custom:custom108`|`Use Field Value`|_any_||[Blank]|Orange Icon with cogs|Issue #90|
|`custom:custom108`|_any_|_any_|`XYZ`|[Blank]|Orange Icon with `XYZ`|Issue #90|
|`/img/samples/color_red.gif`|`Use Icon Only`|_any_|[Blank]|[Blank]|Red Square|Issue #90 and #91|

# Numeric Field
## Simple Setup
|Icon or Image|Empty Static Text Behavior|Zero Value Handling|Static Text|Field Value|Display Result|Status|
|---------|-----|------|-------|------|-----|-----|
|`standard:groups`|`Use Field Value`|_any_||`1`|Group Icon color with `1`|
|`standard:groups`|`Use Field Value`|`Treat Zeros as Numbers`||`0`|Group Icon color with `0`|
|`standard:groups`|`Use Icon Only`|_any_||`1`|Group Icon|
|`standard:groups`|`Use Icon Only`|`Treat Zeros as Numbers`||`0`|Group Icon|
|`standard:groups`|`Use Field Value`|`Treat Zeros as Numbers`||`0`|Group Icon with `0`|
|`standard:groups`|`Use Field Value`|`Treat Zeros as Blanks`||`0`|No Icon|
|`standard:groups`|`Use Field Value`|_any_||`1`|Group Icon with `1`|Note Only first 3 numbers will be shown, so 1000 will show as 100. Not recommended|
|`standard:groups`|_any_|`Treat Zeros as Blanks`|`EMP`|`0`|No Icon|
|`standard:groups`|_any_|`Treat Zeros as Numbers`|`EMP`|`0`|Group Icon color with `EMP`|Only showing Group Icon or Field Value. Issue #92|
|`standard:groups`|_any_|_any_|`EMP`|`1`|Group Icon color with `EMP`||

Images will be tested once Issue #91 is resolved

## Inverse Setup
`Show when False or Blank` is `true`
|Inverse Icon Value or Image|Empty Static Text Behavior|Zero Value Handling|Inverse Static Text|Field Value|Display Result|Status|
|---------|-----|------|------|-----|-----|-----|

Will be tested once Issue #90 is resolved