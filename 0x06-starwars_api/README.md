# 0x06. Star Wars API

## Overview

The **Star Wars API** project is designed to interact with an external API to fetch and display information about characters from the Star Wars universe based on a given movie ID. The main objective is to understand how to make HTTP requests in Node.js, handle asynchronous operations, and work with JSON data.

## Learning Objectives

By completing this project, you will learn:

- How to make HTTP requests in JavaScript using the `request` module.
- How to interact with RESTful APIs and parse JSON responses.
- How to manage asynchronous code execution using callbacks in JavaScript.
- How to parse and utilize command-line arguments in Node.js.
- How to manipulate arrays to process and display data.

## Requirements

- All files should be interpreted on Ubuntu 20.04 LTS using Node.js version 10.x.
- Your code should comply with the semistandard style guide.
- You must use the `request` module for making HTTP requests.
- No `var` declarations are allowed. Use `let` or `const` instead.
- All files should be executable.
- Your code should be documented, including all modules, classes, and functions.

## Setup

### Prerequisites

Ensure you have Node.js and npm installed on your machine. You can install them using the following commands:

```bash
# Install Node.js 10.x
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs

# Verify installation
node -v
npm -v
```
# Install semistandard globally
sudo npm install semistandard --global

# Install request module globally
sudo npm install request --global

# Set NODE_PATH for global modules
export NODE_PATH=/usr/lib/node_modules

