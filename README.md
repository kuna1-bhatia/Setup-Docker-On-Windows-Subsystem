​🐳 Docker Setup for WSL 2
​A streamlined guide to getting your Docker environment running smoothly on Windows Subsystem for Linux.
​🚀 Quick Start Guide
​🔹 Step 1: Install Docker Desktop
​Before touching the terminal, you need the core engine installed on your Windows host.
​Download: Docker Desktop for Windows
​Install: Run the installer and ensure the "Use WSL 2 instead of Hyper-V" option is checked during installation.
​Verify: Open Docker Desktop and wait for the whale icon in the system tray to turn steady green.
​Status Check: Look for Docker Engine running ✅
​🔹 Step 2: Enable WSL Integration (Crucial)
​This step bridges the gap between your Windows Docker installation and your Ubuntu/Linux terminal.
​Open Docker Desktop Settings (gear icon).
​Navigate to Resources ➡️ WSL Integration.
​Ensure the following toggle is ON:
​Enable integration with my default WSL distro
​Under Enable integration with additional distros, toggle Ubuntu (or your preferred distro) to ON.
​Click Apply & Restart.
