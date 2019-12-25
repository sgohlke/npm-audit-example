# npm-audit-example
https://github.com/sgohlke/npm-audit-example/workflows/Run%20audit%20example/badge.svg

Example of using npm audit

## Precondition
To run npm audit the defined modules have to be installed calling

**npm install**
 
For executing npm audit only it should be sufficient to create only the *package-lock.json* calling

**npm install --package-lock-only**


## Module Check
To execute a module scan you can call the following command from command line:

**npm audit**

This will show the results in the command line.

## Dependency Tree
To create a dependency tree the following command can be used: 

**npm ls**
 
This will show a dependency tree in the command line.

## Update Check
If you want to check the used modules for updates you can achieve this using the command 

**npm outdated**

This will show a list of updates available for the used modules.

## Useful links
* [npm-audit](https://docs.npmjs.com/cli/audit)