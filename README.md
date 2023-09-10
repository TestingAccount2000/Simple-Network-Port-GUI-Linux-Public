# Simple-Network-Port-GUI-Linux

## Introduction

This is a simple, open source tool to allow the adding of custom firewall rules based on port. It allows you to block or allow certain ports by adding them to your Linux Ports list. You can then list your custom firewall rules or export them to a text document in the same directory as where the script or the compiled binary is. 

This distributable comes in two forms within each separate directory: a python script "Simple Network Port GUI (Linux).py" and a pre-compiled executable, "Simple Network Port GUI (Linux)"

## UI

![ToolPictureLinux](https://github.com/TestingAccount2000/Simple-Network-Port-GUI-Linux/assets/98635532/3241c58f-1d59-414a-aa59-d72c8bd7c96c)


## Commonly Asked Questions

Q: “When I run the executable or python code, I get no outputs or response?”

A: Run the file or executable as administrator/root. Unfortunately you need to typically on accounts, so if you have any qualms about admin executables, review the code yourself then run the python file. Alternatively, make sure you have some custom port rules already made, this program will not display ones made using other programs.


Q: “My antivirus is saying the executable is a Trojan Virus?” 

A: Antivirus software will (rightfully) recognize random, unsigned executables as viruses typically. This is not one, but if you rather not take the risk just review the python code and run it yourself.

## Future Planned Improvements

1. Replace port rule inputs with radio buttons where applicable (for two choice options)
2. Improve speed of operations
3. Add option to ask user for elevated permissions at start of script
4. Incorporate the entire port firewall ruleset in Linux for editting
