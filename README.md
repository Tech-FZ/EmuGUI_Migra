# EmuGUI Migra

The migration tool for the upcoming EmuGUI 2.1 "Fatima Nejla" update.

## Build

This is still in progress, but here is what you need to do.

### Windows

Prerequisites for building on Windows (just a recommendation):
- Windows 10 Version 2004, Server 2022 or later (64-bit)
- At least an amd64 Dual-Core CPU, preferably with 4 threads
- Preferably at least 8 GB of RAM your OS can actually use (4 GB might work, but you might run into issues)

I recommend the following:
- A Quad-Core CPU, preferably with 8 threads
- 16 GB of RAM your OS can actually use

1. Install (Python)[https://www.python.org].
2. Please avoid Notepad. It is pre-installed on Windows, but coding in there will be really hard. Instead, install a Python IDE or code editor of your choice. Python itself comes with IDLE if you want or need to save space.
3. Create a virtual environment (venv) somewhere. Open a command prompt/PowerShell/terminal window in the direcory you want to have it in and type `python -m venv your-venv-name`, replacing `your-venv-name` with the actual venv name.
4. Activate your venv. In PowerShell, it would be `C:\path\to\your-venv-name\Scripts\Activate.ps1`, however, check your code editor for better approaches.
5. Install the modules using `pip install PySide6 pyinstaller pywin32`.