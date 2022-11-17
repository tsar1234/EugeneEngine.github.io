:wait
timeout /t 1
GOTO :kill

:kill
taskkill /IM "ClassroomWindows.exe" /F
GOTO :wait
