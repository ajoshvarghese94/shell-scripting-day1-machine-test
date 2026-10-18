# Shell Scripting Day-1 Machine Test

**Student Name:** Ajosh
**Batch:** 09:15 - 10:15
**Date:** 19-10-2026

## Scripts

| Script | Description |
|--------|-------------|
| `welcome.sh` | Prints "Welcome to Linux" and "Learning Shell Scripting" using a Bash shebang. |
| `student.sh` | Stores student name, course and batch in variables and displays them with echo. |
| `userinfo.sh` | Reads name and course from the user with `read` and prints a welcome message. |
| `systeminfo.sh` | Shows current user, home directory and shell using `$USER`, `$HOME`, `$SHELL`. |
| `report.sh` | Stores date and logged-in user using command substitution `$(...)` and displays them. |
| `automation.sh` | Prints a server report: date/time, user, uptime and disk usage. |

## Task 6 - Script Execution (welcome.sh)

```bash
ls -l welcome.sh      # check current permissions (-rw-r--r--)
chmod +x welcome.sh   # add execute permission
ls -l welcome.sh      # now shows -rwxr-xr-x
./welcome.sh          # execute the script
```

## Task 8 - Error Identification

| Wrong | Problem | Correct |
|-------|---------|---------|
| `user name="John"` | Variable names cannot contain spaces | `user_name="John"` |
| `1name="John"` | Variable names cannot start with a digit | `name1="John"` |
| `name = "John"` | No spaces allowed around `=` | `name="John"` |
