# Passgen: A simple CLI based Password Generator
Node.js command line app to generate random passwords

## Features
1. Password copied to clipboard automatically
2. Save to file
3. Customize: 
    * Length  
    * No Symbols
    * No Numbers

## Usage

Install dependencies

```
npm install
```

Run file

```
node index (options)
```

To create a symlink to run "passgen" from anywhere

```
npm link

# Now you can run
passgen (options)

# To remove symlink
npm unlink
```

## Options

| Short | Long              | Description                     |
| ----- | ----------------- | ------------------------------- |
| -l    | --length <number> | length of password (default: 8) |
| -s    | --save            | save password to passwords.txt  |
| -nn   | --no-numbers      | remove numbers                  |
| -ns   | --no-symbols      | remove symbols                  |
| -h    | --help            | display help for command        |
| -V    | --version         | Show the version                |
