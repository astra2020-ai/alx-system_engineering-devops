### 0x03. Shell, init files, variables and expansions
Types of variables
As seen in the examples above, shell variables are in uppercase characters by convention. Bash keeps a list of two types of variables:
## Global variables
Global variables or environment variables are available in all shells. The env or printenv commands can be used to display environment variables. These programs come with the sh-utils package.

## Local variables
Local variables are only available in the current shell. Using the set built-in command without any options will display a list of all variables (including environment variables) and functions. The output will be sorted according to the current locale and displayed in a reusable format.
