<div align="center">

## get Font types on computer


</div>

### Description

This code takes every font from the computer it is run on, and places it into a combo box. (not using printer.fonts but using screen.fonts)
 
### More Info
 
Must have a combo box called ftype


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[V\. B\. Fool](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/v-b-fool.md)
**Level**          |Unknown
**User Rating**    |5.0 (5 globes from 1 user)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/v-b-fool-get-font-types-on-computer__1-1602/archive/master.zip)





### Source Code

```
''for loop adds all font types in computer to combo box
  fType.Clear  ''clears combo box
  For i = 0 To Screen.FontCount - 1 ''counts # of fonts
    fType.AddItem Screen.Fonts(i) ''adds font to combo box
  Next i
```

