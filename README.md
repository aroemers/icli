# icli

Wrap any command in an interactive shell

## Install

Copy the `icli` script somewhere on your PATH, and ensure it's executable (`chmod +x icli`).

## Usage

For example with the [`reminders-cli`](https://github.com/keith/reminders-cli) tool:

```sh
$ icli reminders
Entering interactive shell for reminders. Type 'exit' to quit.

> show-lists
Todo
Holiday
Groceries

> add groceries apples
Added 'apples' to 'Groceries'

> exit
$ 
```
