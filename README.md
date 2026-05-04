# Airport Gap API Test Suite

This is an automated API test collection for [Airport Gap](https://airportgap.com/).

## Requirements

- [Bruno](https://www.usebruno.com/) (Desktop app)
- [Node.js](https://nodejs.org/) (For CLI automation)

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Configure Credentials:
   - Open the collection in Bruno.
   - Edit the Production environment.
   - Fill in your email and password for the Airport Gap API.
   - If you don't have an account, register at https://airportgap.com/tokens (via the API or site).

## Running Tests

To run the automated tests via CLI:
```bash
npm test
```

## Collection Structure

- **Airports**: Tests for listing and retrieving airport details.
- **Distance**: Tests for calculating distance between airports.
- **Authentication**: Tests for token generation.
- **Favorites**: Tests for managing favorite airports (Requires authentication).
