# Solidity Audit Recipes

## Content

A collection of [Goose recipes](https://block.github.io/goose/docs/quickstart).

## Install

```bash
$ npm install -g giget

$ giget gh:TilakMaddy/solidity-audit-recipes/.goose .goose --force
```

Run the above commands at the project root to import these recipes.

## Audit

### Step 1

Install [Aderyn](https://github.com/cyfrin/aderyn) which provides an MCP server that provides guidance to AI agents

```bash
aderyn mcp http-stream --port 3001
```
Run the above command at project root.

### Step 2

Open [Goose Desktop](https://block.github.io/goose/docs/getting-started/installation) and set the working directory to the project root. 

### Step 4

In the **Extension** tab, add Aderyn's MCP server. Fill in the name, type, description, endpoint and timeout as shown below

<img height="620" alt="Screenshot 2025-09-21 at 11 14 44 PM" src="https://github.com/user-attachments/assets/c1946882-1aff-49e6-9d86-e089784677ee" />

### Step 5

Then from the **Recipes** tab, select **Use** on the ones you are interested in.

<img width="720" alt="recipes" src="https://github.com/user-attachments/assets/845e61f3-b5b0-4cc6-a451-dcc3e82d53f8" />
