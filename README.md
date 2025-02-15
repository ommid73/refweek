# refweek

<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN">
<html><head><title>Python: module Automater</title>
</head><body bgcolor="#f0f0f8">

<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="heading">
<tr bgcolor="#7799ee">
<td valign=bottom>&nbsp;<br>
<font color="#ffffff" face="helvetica, arial">&nbsp;<br><big><big><strong>Automater</strong></big></big></font></td
><td align=right valign=bottom
><font color="#ffffff" face="helvetica, arial"><a href=".">index</a><br><a href="file:/home/jim/Files/TekDefense/TekDefense-Automater-Private/Automater.py">/home/jim/Files/TekDefense/TekDefense-Automater-Private/Automater.py</a></font></td></tr></table>
    <p><tt>The&nbsp;Automater.py&nbsp;module&nbsp;defines&nbsp;the&nbsp;<a href="#-main">main</a>()&nbsp;function&nbsp;for&nbsp;Automater.<br>
&nbsp;<br>
Parameter&nbsp;Required&nbsp;is:<br>
target&nbsp;--&nbsp;List&nbsp;one&nbsp;IP&nbsp;Address&nbsp;(CIDR&nbsp;or&nbsp;dash&nbsp;notation&nbsp;accepted),&nbsp;URL&nbsp;or&nbsp;Hash<br>
to&nbsp;query&nbsp;or&nbsp;pass&nbsp;the&nbsp;filename&nbsp;of&nbsp;a&nbsp;file&nbsp;containing&nbsp;IP&nbsp;Address&nbsp;info,&nbsp;URL&nbsp;or<br>
Hash&nbsp;to&nbsp;query&nbsp;each&nbsp;separated&nbsp;by&nbsp;a&nbsp;newline.<br>
&nbsp;<br>
Optional&nbsp;Parameters&nbsp;are:<br>
-o,&nbsp;--output&nbsp;--&nbsp;This&nbsp;option&nbsp;will&nbsp;output&nbsp;the&nbsp;results&nbsp;to&nbsp;a&nbsp;file.<br>
-w,&nbsp;--web&nbsp;--&nbsp;This&nbsp;option&nbsp;will&nbsp;output&nbsp;the&nbsp;results&nbsp;to&nbsp;an&nbsp;HTML&nbsp;file.<br>
-c,&nbsp;--csv&nbsp;--&nbsp;This&nbsp;option&nbsp;will&nbsp;output&nbsp;the&nbsp;results&nbsp;to&nbsp;a&nbsp;CSV&nbsp;file.<br>
-d,&nbsp;--delay&nbsp;--&nbsp;Change&nbsp;the&nbsp;delay&nbsp;to&nbsp;the&nbsp;inputted&nbsp;seconds.&nbsp;Default&nbsp;is&nbsp;2.<br>
-s,&nbsp;--source&nbsp;--&nbsp;Will&nbsp;only&nbsp;run&nbsp;the&nbsp;target&nbsp;against&nbsp;a&nbsp;specific&nbsp;source&nbsp;engine<br>
to&nbsp;pull&nbsp;associated&nbsp;domains.&nbsp;&nbsp;Options&nbsp;are&nbsp;defined&nbsp;in&nbsp;the&nbsp;name&nbsp;attribute&nbsp;of<br>
the&nbsp;site&nbsp;element&nbsp;in&nbsp;the&nbsp;XML&nbsp;configuration&nbsp;file<br>
--p&nbsp;--post&nbsp;--&nbsp;Tells&nbsp;the&nbsp;program&nbsp;to&nbsp;post&nbsp;information&nbsp;to&nbsp;sites&nbsp;that&nbsp;allow&nbsp;posting.<br>
By&nbsp;default&nbsp;the&nbsp;program&nbsp;will&nbsp;NOT&nbsp;post&nbsp;to&nbsp;sites&nbsp;that&nbsp;require&nbsp;a&nbsp;post.<br>
--proxy&nbsp;--&nbsp;This&nbsp;option&nbsp;will&nbsp;set&nbsp;a&nbsp;proxy&nbsp;(eg.&nbsp;proxy.example.com:8080)<br>
-a&nbsp;--useragent&nbsp;--&nbsp;Will&nbsp;set&nbsp;a&nbsp;user-agent&nbsp;string&nbsp;in&nbsp;the&nbsp;header&nbsp;of&nbsp;a&nbsp;web&nbsp;request.<br>
is&nbsp;set&nbsp;by&nbsp;default&nbsp;to&nbsp;Automater/version#<br>
&nbsp;<br>
Class(es):<br>
No&nbsp;classes&nbsp;are&nbsp;defined&nbsp;in&nbsp;this&nbsp;module.<br>
&nbsp;<br>
Function(s):<br>
main&nbsp;--&nbsp;Provides&nbsp;the&nbsp;instantiation&nbsp;point&nbsp;for&nbsp;Automater.<br>
&nbsp;<br>
Exception(s):<br>
No&nbsp;exceptions&nbsp;exported.</tt></p>
<p>
<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="section">
<tr bgcolor="#aa55cc">
<td colspan=3 valign=bottom>&nbsp;<br>
<font color="#ffffff" face="helvetica, arial"><big><strong>Modules</strong></big></font></td></tr>
    
<tr><td bgcolor="#aa55cc"><tt>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</tt></td><td>&nbsp;</td>
<td width="100%"><table width="100%" summary="list"><tr><td width="25%" valign=top><a href="sys.html">sys</a><br>
</td><td width="25%" valign=top></td><td width="25%" valign=top></td><td width="25%" valign=top></td></tr></table></td></tr></table><p>
<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="section">
<tr bgcolor="#eeaa77">
<td colspan=3 valign=bottom>&nbsp;<br>
<font color="#ffffff" face="helvetica, arial"><big><strong>Functions</strong></big></font></td></tr>
    
<tr><td bgcolor="#eeaa77"><tt>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</tt></td><td>&nbsp;</td>
<td width="100%"><dl><dt><a name="-main"><strong>main</strong></a>()</dt><dd><tt>Serves&nbsp;as&nbsp;the&nbsp;instantiation&nbsp;point&nbsp;to&nbsp;start&nbsp;Automater.<br>
&nbsp;<br>
Argument(s):<br>
No&nbsp;arguments&nbsp;are&nbsp;required.<br>
&nbsp;<br>
Return&nbsp;value(s):<br>
Nothing&nbsp;is&nbsp;returned&nbsp;from&nbsp;this&nbsp;Method.<br>
&nbsp;<br>
Restriction(s):<br>
The&nbsp;Method&nbsp;has&nbsp;no&nbsp;restrictions.</tt></dd></dl>
</td></tr></table>
</body></html>

Une interface qui permet de visualiser son futur emploi du temps en tant qu'élève en BA1 à l'EPFL.

Ce programme utilise des données préalablement récupérées à l'aide de [edufetch](https://github.com/epfl-tools/edufetch).

Inspiré par l'[idée](https://github.com/epfl-tools/epfl-weekbuilder) d'[Androz](https://github.com/Androz2091).
Ceci n'est pas un service officiel, l'EPFL n'est pas à l'origine de ce projet.
