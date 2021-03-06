# Scripting and Automation
John Yocum  
![CC BY-SA 4.0](../images/cc_by-sa_4.png)  



# Scripting

## Benefits

- <font color=darkblue>Change tracking</font> (you can store your scripts in a version control system)
- <font color=darkblue>Less prone to errors</font> (every time you run it, it'll be the same)
- <font color=darkblue>Easy to Share</font> (just hand over your code and they can run the same operation)
- <font color=darkblue>You can walk away</font> (you don't have to sit and wait for each step to finish)
- <font color=darkblue>Reference material</font> (well written scripts serve as documentation)

## Languages

**Builtin Options:**

- Bash (or any other shell on Linux or OS X)
- Batch File (Windows)
- Powershell (Windows)

**Other Options:**

- R
- Python
- Perl

## Tips

- Use an editor that offers syntax high-lighting
- Use soft tabs instead of hard tabs
    - Most editors have an option to set TAB to be 4 spaces
    - Code will appear consistent between editors and operating systems
- Logically name variables and functions
    - Names like "DATA_IN" and "DATA_OUT" instead of "FILE1", "FILE2", etc
- Be consistent in your naming convention
- Put comments in your scripts
    - Explain why you are doing something isn't obvious
    - Explain how something works if the code isn't clear
- Use version control software
    - Track code changes
    - Simplify life when multiple people are working on the same scripts
- Don't reinvent the wheel
    - Use packages or libraries when possible

# Automation

## Requirements

- Depends on scripting
- Consistent environment (software and data format)
- Planning
    - Do a dry-run of the processes before automating them
    - Confirm you'll have enough time and resources for everything to finish
    - What will go wrong if the automated process fails
    
## Tips

- Document it
    - What does it do
    - What does it depend on
    - Which computer is it running on (for tasks run on a scheduler)
- Don't reinvent the wheel
    - Check to make sure no one else has already come up with a solution

## Examples

- Fetching and importing data files from an FTP server into a database
- Generating updated charts and graphs from changing data files
- Backing up the contents of a directory

# Questions?
