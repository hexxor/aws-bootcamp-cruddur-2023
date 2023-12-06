# Week 0 — Billing and Architecture
# CloudShell commands:

Enable auto-completion, called auto-prompt. Shows possible commands as a preview, use TAB to accept proposed commands

`aws --cli-auto-prompt`

`aws sts` stands for "Security token service"

# Gitpod usage:

Print environment variables using `env`

Show the $PATH environment variable: `echo $PATH`

Use the aws CLI from within Gitpod after installing it: `aws sts get-caller-identity`

This will generate an error if no credentials have been set in the environment variables.

Save environment variables inside gitpod: `gp env AWS_ACCESS_KEY_ID=defaultvalue`

# Homework

## Create a billing alarm
The limit of the alarm was set to 1 USD
[My own budget set up](assets/budget.png)
