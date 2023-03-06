#!/bin/bash
# inventory.sh
#Author:Nene
#Date:03/05/2023
echo -e "\n\nChecking CPU IFO\n\n"

sleep 3
lscpu

echo -e "\nChecking the processor\n"

sleep 3
nproc

echo -e "\nChecking the OS version\n"

sleep 3
cat /etc/*release

echo -e "\nChecking the OS version\n"

sleep 3
uname -r


echo -e "\nChecking the Hard drive\n"

sleep 3
lsblk

echo -e "\nChecking the system Bits\n"

sleep 3
getconf LONG_BIT



echo -e "\nChecking the Memory\n"

sleep 3
free -m
