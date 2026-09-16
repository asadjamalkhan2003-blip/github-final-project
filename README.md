# Simple Interest Calculator

## Project Description

A Bash-based calculator that calculates simple interest based on the principal amount, annual rate of interest, and time period provided by the user.

## Inputs

* **Principal amount**: The initial sum of money invested or loaned.
* **Rate of interest**: The annual interest rate percentage.
* **Time period**: The duration in years for which the principal is invested or loaned.

## Features

* Accept principal amount as input
* Accept rate of interest as input
* Accept time period as input
* Calculate simple interest accurately
* Display the calculated result clearly

## Formula

The simple interest is calculated using the standard formula:

$$\text{Simple Interest} = \frac{\text{Principal} \times \text{Rate} \times \text{Time}}{100}$$

In text form:
`Simple Interest = (Principal * Rate * Time) / 100`

## How the Calculator Works

1. The script prompts the user to enter the principal amount.
2. The user is then asked to enter the annual rate of interest.
3. The user enters the time period in years.
4. The script computes the simple interest using the formula `(p * t * r) / 100`.
5. The final calculated simple interest is printed to the terminal.

## Project Structure

The project contains a Bash script named `simple-interest.sh` which implements the calculation logic.

## Usage

Make the script executable and run it:

```bash
chmod +x simple-interest.sh
./simple-interest.sh
```

## Author

Asad Jamal
