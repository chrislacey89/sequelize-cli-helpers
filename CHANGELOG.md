## sequelize-cli-helpers

## CHANGELOG

### 0.1.1

- #19 fixed bug, cli was breaking if a `.sequelizeclihelpersrc` file was not present in a project repo

### 0.1.0 

- #1 added first command: `touch`
  - chose and added key dependencies, yargs, enquirer,  
  - added ability to read in `.sequelizerc` if exists
  - created lib funcs, e.g. getDate.js, padNumber.js, etc.
  - created command / handlers for `touch`, able to create 
    a file name of various formats, and create the empty file
- #2 added a README
- #3 added a CHANGELOG
- #4 added a CONTRIBUTING and a SPEC
- #5 added ability to configure based on a `.sequelizeclihelpersrc` file
- #9 added command to generate a migration for a table
- #14 added forceConfirmation option to force user to confirm each string of each file name part

