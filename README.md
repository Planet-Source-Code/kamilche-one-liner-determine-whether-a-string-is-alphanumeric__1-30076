<div align="center">

## One\-liner \- determine whether a string is alphanumeric


</div>

### Description

This one-line function returns whether or not a string consists of only the characters A-Z, a-z, and 0-9.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kamilche](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kamilche.md)
**Level**          |Beginner
**User Rating**    |4.8 (19 globes from 4 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kamilche-one-liner-determine-whether-a-string-is-alphanumeric__1-30076/archive/master.zip)





### Source Code

```
Public Function AlphaNumeric(ByVal s As String) As Boolean
 AlphaNumeric = Not s Like "*[!A-Za-z0-9]*"
End Function
```

