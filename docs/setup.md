# Setup & Installation

## 1. Install Python

Select your operating system to see specific instructions.

=== ":simple-windows: Windows"

    1.  Download the installer from [python.org](https://www.python.org/downloads/).
    
    2.  Run the installer.

    3.  **Critical Step:**
        
        !!! note "Add to PATH"
            Before clicking "Install Now", you **must** check the box at the bottom labeled **"Add python.exe to PATH"**. If you miss this, you cannot run Python from the terminal.

    4.  Verify installation by opening Command Prompt (`cmd`) and running:
        ```cmd
        python --version
        ```

=== ":simple-apple: macOS"

    1.  Download the **macOS 64-bit universal2 installer** from [python.org](https://www.python.org/downloads/).
    
    2.  Run the package installer and follow the prompts.

    3.  Verify installation by opening Terminal and running:
        ```bash
        python3 --version
        ```

=== ":simple-linux: Linux"

    1.  Open your terminal.
    
    2.  Run the update and install commands:
        ```bash
        sudo apt update
        sudo apt install python3 python3-pip python3-venv
        ```

---

## 2. Choose an Editor (IDE)

=== ":simple-visualstudiocode: VS Code"
    **The Industry Standard.** Recommended for most students.
    
    * **Pros:** Huge ecosystem, great for Jupyter Notebooks.
    * **Cons:** Includes Microsoft telemetry.
    
    [Download VS Code](https://code.visualstudio.com/){ .md-button .md-button--primary }

=== ":simple-vscodium: VSCodium"
    **The Open Source Choice.** * **Pros:** Identical to VS Code but with no tracking/telemetry.
    * **Cons:** Updates manually (on Windows).
    
    [Download VSCodium](https://vscodium.com/){ .md-button }
