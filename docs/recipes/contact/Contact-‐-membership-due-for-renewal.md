# Description

This indicator will show a coloured icon when a membership is either due for renewal or is soon to be due for renewal. It will be required to create a custom field indicating whether the membership renewal threshold has been met based on the business rules. For example, whether the member should be contacted after their membership has ended, two weeks, or two months beforehand.

***

# Fields

<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:x="urn:schemas-microsoft-com:office:excel"
xmlns="http://www.w3.org/TR/REC-html40">

<head>

<meta name=ProgId content=Excel.Sheet>
<meta name=Generator content="Microsoft Excel 15">
<link id=Main-File rel=Main-File
href="file:///C:/Users/dall3525/AppData/Local/Temp/msohtmlclip1/01/clip.htm">
<link rel=File-List
href="file:///C:/Users/dall3525/AppData/Local/Temp/msohtmlclip1/01/clip_filelist.xml">

<!--table
	{mso-displayed-decimal-separator:"\.";
	mso-displayed-thousand-separator:"\,";}
@page
	{margin:.75in .7in .75in .7in;
	mso-header-margin:.3in;
	mso-footer-margin:.3in;}
tr
	{mso-height-source:auto;}
col
	{mso-width-source:auto;}
br
	{mso-data-placement:same-cell;}
td
	{padding-top:1px;
	padding-right:1px;
	padding-left:1px;
	mso-ignore:padding;
	color:black;
	font-size:11.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:Calibri, sans-serif;
	mso-font-charset:0;
	mso-number-format:General;
	text-align:general;
	vertical-align:bottom;
	border:none;
	mso-background-source:auto;
	mso-pattern:auto;
	mso-protection:locked visible;
	white-space:nowrap;
	mso-rotate:0;}
.xl65
	{font-weight:700;}
-->

</head>

<body link="#0563C1" vlink="#954F72">


Fields | Value
-- | --
sObject | Contact
Field | Membership expired
Active | TRUE
Description | Indicates to contact for membership renewal
Empty   Static Text Behavior | Use   Icon Only
Show   False or Blank | FALSE
Hover Text | Email the member for membership renewal
Icon Value | standard:email
Icon Background | Green
Icon Foreground | White
Show When False or Blank | TRUE
Inverse Hover Text | Membership is active
Inverse Icon Value | standard:email
Inverse Icon Background | Blue
Inverse Icon Foreground | White



</body>

</html>
