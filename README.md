# Playwright API Tests

This Repo automates API tests for the music tracks endpoint.

## Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

## Setup

1. Clone the repository or extract the ZIP file.
2. Navigate to the project directory and run:

   ```
   npm install
   ```

## Running Tests

Run the tests with:

```
npx playwright test
```

## Below list of Test Scenarios are Automated

SC_1. Validate response status and time.
SC_2. Verify non-empty `id` and `segment_type`.
SC_3. Validate `primary` field in `title_list`.
SC_4. Ensure only one track has `now_playing` set to true.
SC_5. Validate the `Date` header in the response.

## Additional Notes

- Playwright configuration is in `playwright.config.ts`.
- Test definitions are in the `tests/` folder.
        
