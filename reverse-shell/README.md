# Reverse-Shell

All scripts within this folder will open a reverse shell on the machine that's being tested, and will additionally close the terminal where the command ran, in order to avoid easy detection.

# Test

## Step 1
Run

```bash
nc -lvnp 4444
```
in your terminal.

## Step 2

Update the script with your address and port 4444 and execute the script.

# Notes
If someone manages to find an easier way to perform the windows script, please let me know.