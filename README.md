# Using dotenv with Node.js

## How to use

This is an example showing how to store your secrets (credentials) with the library dotenv.


1. Clone this repository: `git clone https://github.com/stackhero-io/dotenvWithNodejs && cd dotenvWithNodejs`

2. Copy the file `.env-example` to `.env` and fill it with your credentials.

3. Install dependencies: `npm install`.

4. Run the script: `npm run start`.


## How does it works

The credentials for your development platform are stored directly in the file `.env`.
This file should not be stored in your git repository. An entry has been added to the file `.gitignore` for that purpose.

On your development platform (on Stackhero), you can define your secrets in your Node.js service configuration for your development platform.

Thanks to that, you'll have different credentials for your development and your production platform and you will not store any credentials on your git repository: you get flexibility and security at the same time!