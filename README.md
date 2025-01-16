# Shamir's Secret Sharing Implementation

This project implements a simplified version of Shamir's Secret Sharing algorithm using Angular.

## Prerequisites

- Node.js (v18 or higher)
- npm (comes with Node.js)

## Setup Instructions

1. Unzip the project files to your desired location:
   ```bash
   unzip catalog.zip
   cd catalog
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:4200`

## Project Structure

- `src/app/models/` - Contains the TestCase and Point interfaces
- `src/app/services/` - Contains the PolynomialService and SecretSharingService
- `src/main.ts` - Main application entry point with test cases

## Test Cases

The application includes two test cases:
1. A simple test case with n=4, k=3
2. A complex test case with n=10, k=7

The results (constant terms) for both test cases are displayed on the main page.

## Implementation Details

- Uses Lagrange interpolation to find the constant term
- Supports various number bases for input values
- Handles large numbers using BigInt
- Built with Angular 18.1.0

## Author

Nithish
