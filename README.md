# User-Account-Mgmt-Script
A modular Bash application that automates common Linux user-administration tasks through a guided command-line interface

The script wraps native Linux commands with input validation, error handling, and confirmation prompts to make user-management operations safer and easier to perform.

## Features

- View existing user accounts
- Create new users
- Delete users
- Change user passwords
- Update a user's full name
- Change a user's login shell
- Validate usernames and menu selections
- Detect non-existent users
- Handle empty or invalid input
- Display clear success and error messages
- Confirm sensitive operations before execution

## Technologies

- Bash
- Linux / Ubuntu
- Native Linux user-management commands
- Shell conditionals, loops, functions, and exit codes

## Requirements

- A Linux-based operating system
- Bash
- Administrator privileges for account-management operations

The script may use commands such as:

- `useradd`
- `userdel`
- `usermod`
- `passwd`
- `getent`
- `chsh`

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/user-account-management-script.git
cd user-account-management-script
