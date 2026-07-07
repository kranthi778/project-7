# system-hacking-project

# Part 1 – Introduction to the Metasploit Framework

## Objective

The goal here is to get to know the Metasploit Framework. We need to understand what it is used for how it works and how to use it. This will help us do authorized testing in an environment.

# What is the Metasploit Framework?

The Metasploit Framework is a tool that helps security experts test for weaknesses, in systems. They use it to make sure systems are secure.

This tool has parts that help with testing. It can find weaknesses take advantage of them and even help fix problems.

In this project we will only use Metasploit in a controlled lab. The lab has Kali Linux, Windows 7 and Metasploitable 2.

# Core Components of Metasploit

The Metasploit Framework has types of parts. These include:

- Exploits

- Payloads

- Auxiliary Modules

- Post-Exploitation Modules

- Encoders

- NOP Generators

Each part does a job when testing security.

## 1. Launch the Metasploit Console

### Scenario

We need to start the Metasploit Framework.

### Command

```bash

msfconsole

```

### Description

This command starts the Metasploit Framework console. It also loads all the parts.

### Screenshot

![Alt text](screenshots/msfconsole-start.png)

## 2. Display Available Help Commands

### Scenario

We want to see the help menu.

### Command

```bash

help

```

### Description

This command shows us all the Metasploit commands and how to use them.

### Screenshot

![Alt text](screenshots/msfconsole-help.png)

## 3. View Available Module Categories

### Scenario

We need to list all the module categories in Metasploit.

### Command

```bash

show all

```

### Description

This command shows us all the module categories and the modules we have.

### Screenshot

![Alt text](screenshots/show-all-modules.png)

## 4. Display Framework Version

### Scenario

We want to know what version of Metasploit we have.

### Command

```bash

version

```

### Description

This command tells us what version of the Metasploit Framework we are using.

### Screenshot

![Alt text](screenshots/metasploit-version.png)

# Key Concepts Learned

- Metasploit Framework

- Module Categories

- Exploits

- Payloads

- Auxiliary Modules

- Post Modules

# conclusion

In this part I learned:

- What the Metasploit Framework is used for.

- What module categories are available.

- How to use the Metasploit console.

- How to check what version of Metasploit I have.
