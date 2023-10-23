# Broadway Lottery

## Overview

The project was created to help sign up for Broadway musicals lottery tickets. Currently, it works for lotteries on the Broadway Direct website. The list of musicals is defined in the [source code](/e2e/broadway-direct.spec.ts#L14). You can edit that list directly on the website. The signup process is run at around 11 a.m. EST. The results are usually available around 3 p.m. EST. Enjoy the shows and please use this automation responsibly.

## How to use it

1. Fork the repository
2. Go to Settings of the repository and add the necessary secrets ([instructions](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions))

### Secrets variables

The following variables are needed to run the signup automation. Replace the values with info about yourself:
```
FIRST_NAME: Donald
```
```
LAST_NAME: Duck
```
```
NUMBER_OF_TICKETS: 2
```
```
EMAIL: donald.duck@gmail.com
```
```
DOB_MONTH: 12
```
```
DOB_DAY: 12
```
```
DOB_YEAR: 2001
```
```
ZIP: 10007
```
```
COUNTRY: USA
```
