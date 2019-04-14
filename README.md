# the ping of health

## Problem Statement 1

I have many home devices (IoT).
How do I know if all my devices are patched?

Do I know even know many devices I have?

## User Story:

As a homeowner of many devices, 
I want to know which home devices are outdated and vulnerable to known exploits, 
so that I can patch them.

## Audience:

Tech savvy (multiple devices)
     +
Security aware (wants to get latest patch)
     +
Not security trained (easy to use)


## Possible Solution

A mobile app that scans the home network and gathers information necessary to check if devices are updated to the latest version and notifies the user.

However, we have some problems:
* Requires Data from Home Devices
* Requires Data of All Known Devices
* Requires the Logic to Check and Notify

These are the gaps identified:
1. Requires Data from Home Devices
   - Home devices do not usually respond, or are inconsistent, with OS or firmware versions
1. Requires Data of All Known Devices
   - Where is the CVEDetails.com equivalent of database for known versions for home devices?


## POC Demo

[Add Device Record to Database](https://ping-of-health.github.io/thepingofhealth.com/add-device-update.html(target|_blank)")

[Query Device from Database](https://ping-of-health.github.io/thepingofhealth.com/get-device-update.html"(target|_blank)")

