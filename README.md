# GitHub User Fetcher

## Summary
This is a simple web application that allows users to fetch the account creation date of a GitHub user by entering their username.

## Setup
1. Clone the repository or download the files.
2. Open `index.html` in a web browser.

## Usage
1. Enter a GitHub username in the input field.
2. Click the 'Fetch' button to retrieve the account creation date.

## Code Explanation
- The form with id `github-user-12345` captures the username input.
- On form submission, the application fetches the account creation date from the GitHub API.
- The status of the lookup is reported in an aria-live alert with id `github-status`.
- The account age is displayed in whole years inside the element with id `github-account-age`.
- The last successful lookup is cached in localStorage and repopulated on page load.

## License
This project is licensed under the MIT License.