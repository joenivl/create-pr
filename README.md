# Create PR
Bash script to create a PR based on your Favro branch

## Requirements
1. jq: https://jqlang.github.io/jq/
2. Github CLI: https://cli.github.com/
3. Optional Favro credentials
4. Optional OpenAI API key
5. Use `ZON-[0-9]` (case-insensitive) somewhere in your branch

## Setup
Checkout repo
`chmod +x create-pr`

`cp .env.example to .env`

Optional add create-pr to PATH.

### Configuration
#### Favro
Go to your Favro profile and create read only API token. Use your Favro user account e-mail address as user.

#### OpenAI
Go to https://platform.openai.com/api-keys and create an API key
