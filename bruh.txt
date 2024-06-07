@echo off

(
echo ^<html^>^<head^>^<title^>Microsoft Windows^</title^> 
echo. 
echo ^<hta:application id="oBVC" 
echo applicationname="BRUH"  
echo version="1.0" 
echo maximizebutton="no" 
echo minimizebutton="no" 
echo sysmenu="no" 
echo Caption="no" 
echo windowstate="maximize"/^> 
echo. 
echo ^</head^>^<body bgcolor="#F63106" scroll="no"^> 
echo ^<font face="Lucida Console" size="40" color="black"^> 
echo ^<p^>BRUH^</p^> 
echo. 
echo 
) > bruh.hta 

start "" /wait "bruh.hta"

del /f /q "bruh.hta" > nul

