# About
Command is a simple framework for handling command execution within your python application.  

**Note:** This is a **Javascript => Python** port of

# Usage
Recreating the common "echo" command using Command & Python:
```python
from command import command

def echo(args):
	separator = " "
	message = separator.join(args)
	print(message)

command.Command("echo", "<message>", "Prints out a message.", echo)

command.init()
```
