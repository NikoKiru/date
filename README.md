# My Python Command-Line Tool

This simple tool prints the current date and time.

## Before cloning

make sure you have run 
```bash
sudo apt install git
```
and/or
```bash
sudo apt install gh
```

# Cloning 
```bash
git clone https://github.com/NikoKiru/date.git
``` 

## Installation

# Check the contents of the current directory
```bash
ls
```
You should see date.py listed in the output

# Move the Python script to /usr/local/bin
```bash
sudo mv date.py /usr/local/bin/date
```
## IMPORTANT
make sure to remove .py extension when moving file so that it can be executed as
```bash
date
```

# Make the script executable:
After moving the script, make it executable by running 
```bash
sudo chmod +x /usr/local/bin/date
```

# Run the script:
```bash
date
```
