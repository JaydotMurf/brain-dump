# Windows Subsystem for Linux (WSL) Overview 📚

WSL allows running a Linux environment directly on Windows without needing a virtual machine or dual-boot setup.

Documentation: [WSL Documentation](https://learn.microsoft.com/en-us/windows/wsl/)

## Quick Installation Guide 💻

**Step 1:** Open PowerShell or Command Prompt as Administrator.

- **Enable WSL:**

  ```powershell
  wsl --install
  ```

- **Verify Installation & WSL Version:**

  ```powershell
  wsl --list --verbose
  ```

- **Set Default WSL Version (Optional):**

  ```powershell
  wsl --set-version <Distro> 2
  ```

  Replace `<Distro>` with your Linux distribution name.

**Step 2:** Install your preferred Linux distribution from the Microsoft Store.

- Search for Linux distributions (e.g., Ubuntu, Debian).
- Click "Install" on your chosen distribution.

**Step 3:** Launch Linux Distribution.

- Open from the Start menu or run the distribution name via command line.

**Note:** First launch may take a few minutes to complete the installation.

## Tips & Tricks 🛠

- **Access Windows Files from Linux:**
  Navigate to `/mnt/c` to access your C: drive files.

- **Run Windows Commands from Linux:**
  Use `cmd.exe` or `powershell.exe` for executing Windows commands.
