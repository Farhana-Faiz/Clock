# Clock

@echo off
Title Clock
@mode con cols=30 lines=7
color03
: main
cls
echo.
echo Time: %time%
echo.
echo Date: %date%
echo.
ping -n 2 0.0.0.0>nul
goto main
