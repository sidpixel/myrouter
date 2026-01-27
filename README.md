# AutoBuild - Build OpenWrt Firmware Based on Lienol Repo

AutoBuild is an automated solution for building OpenWrt firmware using the [Lienol OpenWrt 19.07](https://github.com/Lienol/openwrt) repository with GitHub Actions. This project aims to simplify the process of building custom OpenWrt firmware, while also fixing compilation errors and updating dependencies such as Go and Dropbear versions.

## Features

- **Automated Build with GitHub Actions:** Automatically triggers the build process on GitHub every time the repository is updated.
- **Fix Compilation Failures:** Resolves known issues in Lienol's OpenWrt repository to ensure successful builds.
- **Version Updates:** Includes updates for key dependencies, such as Go and Dropbear, to ensure compatibility and security.
- **Customizable Builds:** Easily customize the build configurations, including selecting the target devices and packages to include.

## Prerequisites

Before using this project, make sure you have the following:

- **GitHub Account:** You need a GitHub account to fork and interact with the repository.
- **Basic Knowledge of OpenWrt:** Understanding OpenWrt firmware and how it works will help you customize builds.
- **Git and GitHub Actions Familiarity:** Understanding the basics of version control and GitHub Actions will allow you to manage the automation flow.

## Repository Structure

- **`/.github/workflows/`** - Contains GitHub Actions workflows for the build automation process.
- **`/feeds/`** - Folder that includes external packages or dependencies for your firmware build.
- **`/config/`** - Contains default configuration files and settings for the OpenWrt build.
- **`/scripts/`** - Scripts for automating tasks like cleaning, updating dependencies, and fixing issues.
- **`/files/`** - Files such as custom patches or configurations that will be included in the firmware.

## Setup Guide

### 1. Fork the Repository

Start by forking this repository to your own GitHub account:

- Go to the [sidpixel OpenWrt 19.07 repository](https://github.com/sidpixel/op).
- Fork the repository to your GitHub account by clicking the "Fork" button in the top-right corner.

### 2. Clone the Forked Repository

Clone your forked repository to your local machine:

```bash
git clone https://github.com/sidpixel/op.git
cd openwrt
