@echo off
color 55
echo "Do You Like  swiming...? "
echo "Y / N ? "
set /p like=
if %like%==yes goto like
if %like%==no goto virous
:like
echo "phelps : good answer (: "
echo "phelps : i love you ^_^ "
echo "phelps : see you soon.. "
pause
exit

:virous
echo " phelps : OMG..!, but i love you"
echo "phelps : i will drown you in the sea :( "
echo " your device will drown with you and shut off in 10 seconds ): "

timeout 10
shutdown -s -t 100