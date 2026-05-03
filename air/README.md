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
