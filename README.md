# cool
Simple and practical
import os

# List of program names to close
programs_to_close = ['chrome.exe', 'discord.exe', 'skype.exe']

# Loop through the list and close each program
for program in programs_to_close:
    os.system('TASKKILL /F /IM ' + program)
