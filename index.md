<!DOCTYPE html>
<html>
<body bgcolor="#008080"text="#000000"link="#00FF00">
<body>
<head>
<title>Orakul74</title>
</head>

<center>
<TABLE border=0 width=100%>
<TR><TD bgcolor="#ffff00"></TD></TR>
<TR><TD bgcolor="#ff0000"></TD></TR>
<TR><TD bgcolor="#00ff00"></TD></TR>
</TABLE>
<TABLE border=0 width=100%>
<TR><TD bgcolor="#00ff00"></TD></TR>
<TR><TD bgcolor="#ff0000"></TD></TR>
<TR><TD bgcolor="#ffff00"></TD></TR>
</center>
<script type="text/javascript">
var count = -1;
var counter;
var nchar;
var zaderzhka = 300;
var a = new Array();
a[1] = "САЙТ ЗАКРЫТ НА НЕОПРЕДЕЛЕННЫЙ СРОК!";
a[2] = "сайт закрыт на неопределенный срок!";
len = a[1].length;
function animation() {
 count++
 if (count == 0){
   document.volna.display.value = a[1];
 }
 if (count == 1){
   document.volna.display.value = a[2].substring
   (0, 1) + a[1].substring(len, 1);
 }
 if (count > 1){
   a[3] = a[1].substring(0, count - 1) + a[2].substring(count 
   - 1,count) + a[1].substring(len, count);
   document.volna.display.value = a[3];
 }
 if(count == a[1].length){
   count = -1;
 }
 counter = setTimeout("animation()",zaderzhka);
 }
</script>
<center>
  <form name="volna">
    <input name="display" size="37" style="border-style:none;background-color:#008080;font-weight:bold;font-size:27px;color:#00FFFF">
  </form>
  <script type="text/javascript">
animation();
</script>
</center>
</TABLE>

<center><b><i>ஜ════════ஜ۩۞۩ஜ═══════ஜ</i></b></center></p>
"><b><p style="font-size: 37px;"><font color="#00FF00">*******</font></b></a></center></p>

</body>
</html>
