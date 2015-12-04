## Usage

### Prerequisites

Node and npm

### Clone this repo

`git clone https://github.com/browserstack/intern-browserstack.git`

### BrowserStack Authentication

Export the environment variables for the username and access key of your BrowserStack account.
These can be found on the automate accounts page on [BrowserStack](https://www.browserstack.com/accounts/automate)

`export BROWSERSTACK_USERNAME=<browserstack-username>`

`export BROWSERSTACK_KEY=<browserstack-access-key>`

### Run tests

cd to `Local Testing` or `Live Testing` directories for local and live testing respectively.

Install the dependencies using -

`npm install`

Then tests can be run via the command -

`npm test`
