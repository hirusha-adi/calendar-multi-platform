# calendar-multi-platform

multiplatform unix cal command alternative with multiplatform support written in python named `caln`

# Usage

- `caln` - show the current month
- `caln y` - show the current year's calender with all the 12 months
- `caln 2018` - show the calender with all 12 months in the given year

# How to install - Windows

1. Download and install python3. Make sure to check `ADD TO PATH` in the first screen of the python3 installer
2. Run `pip3 install pyinstaller`
3. Download [this file](https://raw.githubusercontent.com/hirusha-adi/calendar-multi-platform/main/caln) and save it as `caln.py`
4. Run `pyinstaller caln.py --onefile --noconfirm`
5. Wait until it is completed
6. Open the `.\dist` folder (in the current working directory)
7. Copy the `caln.exe` to the `%system32%` folder or add the current folder to PATH
8. restart the shell and you can now run `caln` to start the program

# How to install - Linux

1. Install dependencies

   - Ubuntu/Debian

   ```
   sudo apt update && sudo apt install curl python3 python3-pip -y
   ```

   - Arch Linux

   ```
   sudo pacman -Syy curl python3 python3-pip --noconfirm
   ```

   - Red Hat

   ```
    dnf install curl python3 python3-pip
   ```

2. Install the script

```

curl "https://raw.githubusercontent.com/hirusha-adi/calendar-multi-platform/main/caln" >> caln
chmod +x ./caln
sudo mv ./caln /usr/local/bin

```

3. run `caln` in the terminal to start the program
