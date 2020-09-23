<div align="center">

## another version of tempreature converter


</div>

### Description

converts from celcius to fahrenhite and vice versa,

it's a new version of a similar program i submitted before.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[sherif rofael](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sherif-rofael.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |VbScript \(browser/client side\)

**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__4-12.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sherif-rofael-another-version-of-tempreature-converter__4-7742/archive/master.zip)





### Source Code

```
<html dir="rtl">
<head>
<meta http-equiv="Content-Language" content="en-us">
<meta name="GENERATOR" content="Microsoft FrontPage 5.0">
<meta name="ProgId" content="FrontPage.Editor.Document">
<meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<title>New Page 1</title>
<script id=clientEventHandlersVBS language=vbscript>
<!--
Sub B3_onclick
if m.value=1 then
if c.value="" then c.value=0
f.value = (c.value)*9/5 +32
end if
if m.value=2 then
if f.value="" then f.value=0
c.value=((f.value)-32)*5/9
end if
End Sub
Sub Radio1_onclick
'if c.value="" then c.value=0
'f.value = (c.value)*9/5 +32
m.value=1
c.value=""
f.value=""
End Sub
Sub Radio2_onclick
'if f.value="" then f.value=0
'c.value=((f.value)-32)*5/9
m.value=2
c.value=""
f.value=""
End Sub
Sub B2_onclick
c.value=""
f.value=""
End Sub
Sub window_onload
m.value=1
End Sub
-->
</script>
</head>
<body>
<p dir="ltr">&nbsp; </p>
<p dir="ltr"><input type="text" name="m" size="20"></p>
&nbsp;<p dir="ltr">&nbsp;
<INPUT type="radio" name="radio" ID=Radio1> <font color="#0000FF"><b>convert from
Celsius to Fahrenheit</b></font></p>
<p dir="ltr">
&nbsp;
<INPUT type="radio" name="radio" ID=Radio2><font color="#0000FF"><b>convert from
Fahrenheit to Celsius </b></font> </p>
<p dir="ltr">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;<input type="text" name="c" size="23" style="font-family: Comic Sans MS; color: #FF0000; font-weight: bold; font-size: 1em">&nbsp;&nbsp;<font size="5">&nbsp;</font><font size="5" color="#0000FF">Celsius =</font>&nbsp;&nbsp;&nbsp;&nbsp;
<input type="text" name="f" size="18" style="font-family: Comic Sans MS; color: #008000; font-weight: bold; font-size: 1em">&nbsp; <font color="#0000FF" size="5">
Fahrenheit&nbsp;&nbsp;&nbsp;&nbsp;</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </p>
<p dir="ltr">&nbsp;</p>
<p dir="ltr">
<input type="button" value="convert" name="B3" style="font-size: 14pt; font-family: Tempus Sans ITC; font-weight: bold; border-style: double; border-width: 3; padding-left: 4; padding-right: 4; padding-top: 1; padding-bottom: 1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="reset" value="Reset" name="B2" style="color: #800080; font-family: Tempus Sans ITC; font-weight: bold; font-size: 14pt; border-style: dashed; border-width: 3"></p>
<p>&nbsp;</p>
</body>
</html>
```

