# Shell Variables and Expansions

This directory contains shell scripts demonstrating various variable expansions and shell scripting techniques.

## Scripts Overview

### Basic Scripts (0-13)

- **0-alias**: Creates an alias named `ls` that executes `rm *`
- **1-hello_you**: Prints "hello [current_user]"
- **2-path**: Adds `/action` to the PATH environment variable
- **3-paths**: Counts the number of directories in the PATH
- **4-global_variables**: Lists all environment variables
- **5-local_variables**: Lists all local variables, environment variables, and functions
- **6-create_local_variable**: Creates a local variable `BEST=School`
- **7-create_global_variable**: Creates a global variable `BEST=School`
- **8-true_knowledge**: Prints the result of `TRUEKNOWLEDGE + 128`
- **9-divide_and_rule**: Prints the result of `POWER / DIVIDE`
- **10-love_exponent_breath**: Displays `BREATH` to the power of `LOVE`
- **11-binary_to_decimal**: Converts a binary number (stored in `BINARY`) to decimal
- **12-combinations**: Prints all possible combinations of two lowercase letters (a-z), except "oo"
- **13-print_float**: Prints a number (stored in `NUM`) with two decimal places

### Advanced Scripts (100-103)

- **100-decimal_to_hexadecimal**: Converts a decimal number (stored in `DECIMAL`) to hexadecimal
- **101-rot13**: Encodes and decodes text using ROT13 encryption
- **102-odd**: Prints every other line from input, starting with the first line
- **103-water_and_stir**: Performs arithmetic with numbers in custom bases:
  - Converts `WATER` from base "water" (5 digits)
  - Converts `STIR` from base "stir" (4 digits)
  - Adds them and displays the result in base "bestchol" (8 digits)

## Usage

Most scripts use environment variables. Set them before running:

```bash
export VARIABLE_NAME=value
./script_name
```

Some scripts read from stdin:

```bash
echo "input" | ./script_name
```

## Requirements

- Bash shell
- Scripts must be executable (`chmod +x script_name`)
- Some scripts require specific environment variables to be set
