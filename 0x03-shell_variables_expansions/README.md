# 0x03. Shell, init files, variables and expansions

## 📁 Project: alx-system_engineering-devops

This project introduces essential concepts in Shell scripting related to **variables**, **expansions**, **initialization files**, and **command aliasing**. It is part of the ALX Software Engineering Program and provides hands-on tasks that reinforce shell fundamentals crucial for DevOps workflows.

---

## 📚 Learning Objectives

By completing this project, you should be able to:

- Create and use aliases
- Work with shell variables (local and global)
- Use arithmetic and logical shell expressions
- Understand and manipulate the shell `PATH`
- Work with expansions (arithmetic, variable, command, etc.)
- Convert between different data formats (binary to decimal, float formatting, etc.)

---

## 📝 Files and Scripts

Each script in this directory performs a specific shell task:

| Script | Description |
|--------|-------------|
| `0-alias` | Creates an alias `ls` that deletes all files in the current directory |
| `1-hello_you` | Prints `hello user`, where `user` is the current Linux user |
| `2-path` | Adds `/action` to the end of the `PATH` environment variable |
| `3-paths` | Counts the number of directories in the current `PATH` |
| `4-global_variables` | Lists all environment (global) variables |
| `5-local_variables` | Lists all local variables, environment variables, and functions |
| `6-create_local_variable` | Creates a local variable `BEST=School` |
| `7-create_global_variable` | Creates a global variable `BEST=School` |
| `8-true_knowledge` | Adds 128 to the environment variable `TRUEKNOWLEDGE` and prints the result |
| `9-divide_and_rule` | Divides `POWER` by `DIVIDE` environment variables and prints the result |
| `10-love_exponent_breath` | Raises `BREATH` to the power `LOVE` using env variables |
| `11-binary_to_decimal` | Converts binary (stored in `BINARY`) to decimal |
| `12-combinations` | Prints all two-letter combinations except `oo` |
| `13-print_float` | Prints a number (in `NUM`) with exactly 2 decimal places |

---

## 🔧 Usage

Make sure the scripts are executable:

```bash
chmod +x <script_name>
