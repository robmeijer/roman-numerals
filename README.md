# Roman Numerals
This exercise requires you to display the roman numeral for each given number input.

## Setup
First, clone the repository to your computer as follows:
```bash
git clone https://github.com/robmeijer/roman-numerals.git
```

Once it's cloned, change into the new directory, and install the dependencies:
```bash
cd roman-numerals
composer install
```

## Exercise
The code for this exercise should be placed in `functions/roman.php`, in the `roman` function.

The function can accept any whole number as the input.

The function must return the roman numeral for the given number input.

The function only needs to account for numbers up to and including 30.

E.g.:
- `roman(1)` should return `'I'`
- `roman(2)` should return `'II'`
- `roman(6)` should return `'VI'`
- `roman(13)` should return `'XIII'`

### Examples
- 1: 'I'
- 5: 'V'
- 10: 'X'

## Testing
Once the dependencies are installed, the project can be tested by running the automated tests:
```bash
composer test
```
The exercise is complete once all the testcases pass successfully.
