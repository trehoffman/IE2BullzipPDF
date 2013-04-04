IE2BullzipPDF
=============

Windows Powershell script that Prints a webpage to a PDF.

##################################################################################
#
#  Script name: IE2BullzipPDF.ps1 
#  Author:      Trevor Hoffman
#  Homepage:    github.com/trehoffman/IE2BullzipPDF
#
#  Based off of a script from Steve Illichevsky's work on GitHub (stillru/PersonalPakage/Scripts/Powershell/Bullzip-print.ps1)
##################################################################################

DESCRIPTION:

NAME: IE2BullzipPDF.ps1 
Print a webpage as a PDF.

PARAMETERS: 

-In          Input file
-Out         Output PDF file
-PageDelay   Integer denoting how many seconds to wait for IE to load webpage
-PrintDelay  Integer denoting how many seconds to wait for IE to send the page to the PDF printer
-help        Show this help file

SYNTAX:

IE2BullzipPDF.ps1 -In www.google.com  -Out C:\file.pdf

Convert webpage to pdf

IE2BullzipPDF.ps1 -help

Displays the help topic for the script

Additional Information:

This script requires Internet Explorer and Bullzip to be installed on computer
