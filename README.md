# Create PR
Bash script to create a PR based on your Favro branch

## Requirements
1. jq: https://jqlang.github.io/jq/
2. Github CLI: https://cli.github.com/
3. Optional Favro credentials
4. Optional OpenAI API key

## Setup
Checkout repo
`chmod +x create-pr`

`cp .env.example to .env`

Optional add create-pr to PATH.

### Configuration
#### Favro
Go to your Favro profile and create read only API token

#### OpenAI
Go to https://platform.openai.com/api-keys and create an API key
