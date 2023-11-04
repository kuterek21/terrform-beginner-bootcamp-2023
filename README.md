# Terraform Beginner Bootcamp 2023

## Semantic Vesioning :mege:

This is explanation of the Semantic Versioning

[Semantic Versioning](https://semver.org/)


Given a version number MAJOR.MINOR.PATCH, increment the:

- **MAJOR** version when you make incompatible API changes
- **MINOR** version when you add functionality in a backward compatible manner
- **PATCH** version when you make backward compatible bug fixes
Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

## Linux System 

- To check the Linux flavour issue command:
```
cat /etc/os-release
```

## Creating BASH script to fix terraform installation on the startup 

- ** BASH **
[Terraform Installation](https://developer.hashicorp.com/terraform/downloads)

## SHABANG #!

[Shebang (Unix)](https://en.wikipedia.org/wiki/Shebang_(Unix))
- Examples
Some typical shebang lines:

#!/bin/sh – Execute the file using the Bourne shell, or a compatible shell, assumed to be in the /bin directory
#!/bin/bash – Execute the file using the Bash shell
#!/usr/bin/pwsh – Execute the file using PowerShell
#!/usr/bin/env python3 – Execute with a Python interpreter, using the env program search path to find it
#!/bin/false – Do nothing, but return a non-zero exit status, indicating failure. Used to prevent stand-alone execution of a script file intended for execution in a specific context, such as by the . command from sh/bash, source from csh/tcsh, or as a .profile, .cshrc, or .login file.
Shebang lines may include specific options that are passed to the interpreter. However, implementations vary in the parsing behavior of options; for portability, only one option should be specified without any embedded whitespace.[citation needed] Further portability guidelines are found below.

** to run it from everywhere use **
```
source ./bin/install_terraform_cli
``` 
## CHMOD 

[CHMOD](https://en.wikipedia.org/wiki/Chmod)

chmod 666 ./bin/file_name

## Update the gitpod file
 
 - we delete the terraform part and replace with the source ./bin/install_terraform_cli command

 - we also replace the init with the before as per GITPODs documentation
 
 ### Working Env Var

 We can list out all the Enviroment Variables (Env Vars) using ```env``` command

 We can filter specific env var using grep eg. `env | grep AWS_`

 ### Setting and unsetting Env Var 

 In the terminal we can set using 'export PROJ='HELLO_WORLD'

 We can set en var tempoirarly:

 