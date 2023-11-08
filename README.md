# Bash Script for Connecting to Wi-Fi

A simple Bash script for connecting to a Wi-Fi network using the command line. This script is designed to work on Linux systems with NetworkManager and nmcli.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Introduction

This Bash script simplifies the process of connecting to a Wi-Fi network on a Linux system. It utilizes the `nmcli` command, which is a command-line client for NetworkManager. With this script, you can easily list available Wi-Fi networks and connect to a network by providing the SSID and password.

## Prerequisites

Before using this script, ensure that the following prerequisites are met:

- A Linux-based system with NetworkManager installed.
- Administrative privileges to run `nmcli` with `sudo`.

## Installation

1. Download the script to your local machine. You can do this by clicking the "Download ZIP" option from the GitHub repository or by cloning the repository.

2. Make the script executable by running the following command in the terminal:

   ```bash
   chmod +x connect_wifi.sh
