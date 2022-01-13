# calendar-multi-platform

multiplatform unix cal command alternative with multiplatform support written in python named `caln`

# How to install

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

# Usage

- `caln` - show the current month
- `caln y` - show the current year's calender with all the 12 months
- `caln 2018` - show the calender with all 12 months in the given year
