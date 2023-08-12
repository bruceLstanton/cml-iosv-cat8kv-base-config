# IOSv & Cat8kv Base Config for CML
Base Configuration File for IOSv &amp; Cat8kv Devices for CML

## Introduction

This is a baseline/primer configuration for quickly provisioning Cisco **IOSv** and **Cat8000v (Cat8kv)** devices in Cisco Modeling Labs (CML).

## Function

This configuration does the following:
- Sets `enable secret` password
- Sets `username/password`
- Configures `AAA`
- Generates `RSA key` for SSH
- Configures `VTY for SSH login`
- Disables `ip domain lookup`
- Disables ALL `banners` permanently
- Sets `logging synchronous` on console
- Disables `exec-timeout` on console

## Usage
- Clone or download this repository
- Open
- Copy, paste, and save as shown below

![Screenshot](./docs/images/How_To_Use_Base_Configs_In_CML.png)

## Notes

- Neither I nor this project is associated with Cisco Systems, Inc. or VanDyke Software in any way.
- Modify as needed. Change passwords, timeouts, add interfaces, etc.
