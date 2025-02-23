# ALU Shell Project

This project contains scripts for initializing files, variables, and expansions.

## Scripts

### 0-alias
- **Description**: Creates an alias named `ls` that executes `rm *`.
- **Usage**: Run the script to set the alias. Be cautious, as this alias will delete all files in the current directory when `ls` is used.

### 1-hello_you
- **Description**: Prints `hello user`, where `user` is the current Linux user.
- **Usage**: Run the script to display the greeting.

### 2-path
- **Description**: Adds `/action` to the `PATH` environment variable as the last directory the shell searches for programs.
- **Usage**: Run the script to update the `PATH`.

### 3-paths
- **Description**: Counts the number of directories in the `PATH` environment variable.
- **Usage**: Run the script to display the count.

### 4-global_variables
- **Description**: Lists all environment variables.
- **Usage**: Run the script to display the environment variables.

### 5-local_variables
- **Description**: Lists all local variables, environment variables, and shell functions.
- **Usage**: Run the script to display the variables and functions.

### 6-create_local_variable
- **Description**: Creates a new local variable named `BEST` with the value `School`.
- **Usage**: Run the script to create the variable.

### 7-create_global_variable
- **Description**: Creates a new global variable named `BEST` with the value `School`.
- **Usage**: Run the script to create the global variable.

### 8-true_knowledge
- **Description**: Prints the result of adding `128` to the value stored in the environment variable `TRUEKNOWLEDGE`.
- **Usage**: Run the script to calculate and display the result.

### 9-divide_and_rule
- **Description**: Prints the result of dividing the value of the environment variable `POWER` by the value of the environment variable `DIVIDE`.
- **Usage**: Run the script to calculate and display the result.

### 10-love_exponent_breath
- **Description**: Prints the result of `BREATH` raised to the power of `LOVE` (where `BREATH` and `LOVE` are environment variables).
- **Usage**: Run the script to calculate and display the result.

### 11-binary_to_decimal
- **Description**: Converts a binary number (stored in the environment variable `BINARY`) to its decimal equivalent.
- **Usage**: Run the script to convert and display the result.

### 12-combinations
- **Description**: Prints all possible combinations of two lowercase letters (from `a` to `z`), excluding `oo`, in alphabetical order.
- **Usage**: Run the script to generate and display the combinations.

### 13-print_float
- **Description**: Prints a number (stored in the environment variable `NUM`) with two decimal places.
- **Usage**: Run the script to format and display the number.

### 14-decimal_to_hexadecimal
- **Description**: Converts a decimal number (stored in the environment variable `DECIMAL`) to its hexadecimal equivalent.
- **Usage**: Run the script to convert and display the result.

### 15-rot13
- **Description**: Encodes and decodes text using the ROT13 encryption.
- **Usage**: Run the script and provide input text to encode or decode.

### 16-print_every_other_line
- **Description**: Prints every other line from the input, starting with the first line.
- **Usage**: Run the script and provide input text or a file.

### 17-water_and_stir
- **Description**: Adds the two numbers stored in the environment variables `WATER` (in base `water`) and `STIR` (in base `stir`) and prints the result in base `bestchol`.
- **Usage**: Run the script to calculate and display the result.
