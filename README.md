# Textbook

**Author:** Dr. Kelly Gafford, Ph.D.  
**Publisher:** Kendall Hunt Publishing Company

## Welcome!

Welcome to the companion repository for my Linux textbook. This repository provides supplemental files used in the chapter examples, hands-on activities, and practical exercises throughout the book.

Learning Linux isn't about memorizing a long list of commands. It's about understanding what those commands do, why they work, and when to use them. The best way to accomplish that is to open a terminal and start experimenting.

Throughout the book, you'll follow Phred and his phamily as they explore Linux, solve problems, and occasionally create a few of their own. The resources in this repository will help you work through those experiences on your own system.

## What You'll Find Here

Depending on the chapter, companion resources may include:

- Files used in hands-on activities and chapter demonstrations.
- Sample text files, datasets, and simulated system logs.
- Sample configuration files and shell scripts.
- Supplemental materials for practicing Linux commands and system administration.
- Corrections and updates to companion materials, as needed.

Not every chapter requires downloadable files. Refer to the instructions in your textbook to determine which resources you need.

## Recommended Linux Environment

The textbook walkthroughs use **Ubuntu Desktop 26.04.1 LTS** and the **Bash shell**. Many of the commands and exercises will also work on other Linux distributions, including Debian and Fedora. However, package managers, configuration files, and system services may differ.

A dedicated Linux virtual machine is recommended for completing the hands-on activities. Take a snapshot before making significant system changes, if your virtualization software supports snapshots.

## Downloading the Resources

You do not need a GitHub account to download files from a public repository, and you do not need to know Git to complete the activities.

### Option 1: Download Using Your Web Browser

1. Visit [the textbook repository](https://github.com/drkgafford/Textbook).
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the downloaded archive on your Linux system.
5. Locate the files required for the chapter or activity you are completing.

### Option 2: Download Using Git

If Git is already installed on your Linux system, you can download a copy of the repository from the terminal:

```bash
cd ~
git clone https://github.com/drkgafford/Textbook.git
cd Textbook
```

Git is not required for the exercises unless otherwise specified. If you are unfamiliar with Git, use the browser method above.

## Working Through the Activities

- Read the corresponding chapter before beginning an activity.
- Download the required files and follow the activity's preparation instructions.
- Work with copies of the original files so you can start over if necessary.
- Remember that Linux filenames and commands are generally case-sensitive.
- Do not type the `$` or `#` prompt symbols shown at the beginning of textbook command examples.
- Use administrative privileges only when instructed and when you understand why they are needed.
- Examine the output of each command and make sure you understand what happened before continuing.

Your output may differ slightly from the examples in the textbook because of differences in usernames, hostnames, timestamps, software versions, and system configurations.

## A Word of Caution

Some exercises involve modifying files, changing permissions, configuring services, or performing other administrative tasks. Complete these exercises in a dedicated learning environment rather than on a production system or a computer containing important data.

Always understand a command before executing it. Linux generally assumes you know what you're asking it to do. Unfortunately, it doesn't always ask whether you really meant to do it.

A little caution can save you from an RGE — a Résumé Generating Event.

## Reporting Errors

If you discover a missing file, an incorrect example, or another problem with the companion resources, please use the repository's [Issues page](https://github.com/drkgafford/Textbook/issues), if enabled.

When reporting a problem, include the chapter and section or activity number, the filename or command involved, your Linux distribution and version, and a description of the problem. Include relevant error messages, but never post passwords, credentials, or other sensitive information.

## Copyright and Use

The companion materials are provided to support learning and instruction alongside the textbook. Availability through GitHub does not, by itself, place these materials in the public domain or grant an open-source license. Any applicable copyright notices and licensing terms accompanying individual resources should be observed.

---

Don't be afraid to experiment, make mistakes, and ask questions. Troubleshooting those mistakes is often where the real learning takes place.

**Happy Linux-ing!**

— Dr. Kelly Gafford
