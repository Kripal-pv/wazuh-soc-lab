# Week 1 – System Verification

## 1. Network Verification

Command used:

ip a

Confirmed DHCP-assigned IP address.

## 2. System Update

sudo apt update && sudo apt upgrade -y

System updated successfully without errors.

## 3. SSH Verification

Verified SSH service is active and running.

## SSH Installation Fix

Initial error:
Failed to start ssh.service: Unit ssh.service not found

Solution:
Installed OpenSSH server manually using:

sudo apt install openssh-server -y

SSH service started and verified successfully.


## Outcome

System ready for Wazuh installation.
