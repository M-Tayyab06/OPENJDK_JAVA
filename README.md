# Java & Jenkins Installation Guide

A step-by-step guide to install OpenJDK 17/21 and Jenkins on different operating systems.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Install OpenJDK](#install-openjdk)
  - [Ubuntu/Debian](#ubuntu-debian)
  - [CentOS/RHEL](#centos-rhel)
  - [macOS](#macos)
- [Install Jenkins](#install-jenkins)
  - [Ubuntu/Debian](#ubuntu-debian-1)
  - [CentOS/RHEL](#centos-rhel-1)
  - [macOS](#macos-1)
- [Post-Installation](#post-installation)
- [Troubleshooting](#troubleshooting)
- [References](#references)

## Prerequisites
- Administrator/sudo privileges
- Stable internet connection
- Terminal access

## Install OpenJDK

### Ubuntu/Debian
```bash
# Update package index
sudo apt update

# Install OpenJDK 17
sudo apt install openjdk-17-jdk

# Alternatively for OpenJDK 21
sudo apt install openjdk-21-jdk

# Verify installation
java -version
