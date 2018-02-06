# What does it do
Finds and report all managed Windows PCs in K1000 Inventory with a smartcard reader installed.

## Overview
The script is independent by K1000, so if you don't have KACE SMA in your environment don't worry: the script is still useful!

## Components
* [Query] The script :innocent:
* [Reporting] Kace Systems Management Appliance (AKA 'K1000')


## How does it work
The vbs script executes a WMI query over the target device(s) and saves an output file _smartcard.txt_ (see below in the [Setup section](#Setup))

## Setup

Edit [the script](smartcard.vbs) **line 4** with a path where you want to save the output file. In our environment, every PC has a C:\Tools\ directory for service purpose, so i decided to save the output here.