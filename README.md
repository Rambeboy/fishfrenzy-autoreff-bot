## FISHING FRENZY AUTO REFERRAL BOT


## Feature

- **User creation automation**: Automatically create new users with randomly generated usernames.
- **Guest login**: Each user logs in as a guest with a unique device ID.
- **Reff code verification**: Each user tries to verify the provided referral code.
- **Token storage**: The obtained access token is stored in the file `tokens.txt`.

## Prerequisite

- Git
- Node.js (v18 or higher)


## Setup `config.txt`

- Click F12 or CTRL + SHIFT + I 
- Click Network and scroll down search Sessions
- Put PRIVY_APP_ID dan PRIVY_CA_ID enter in the `config.txt`.

## How to run

1. Clone the repository
   ```
   git clone https://github.com/Rambeboy/fishfrenzy-autoreff-bot.git
   ```
2. Navigate to project dir
   ```
   cd fishfrenzy-autoreff-bot
   ```
3. Install dependencies
   ```
   npm install
   ```
4. Run the bot
   ```
   node index.js
   ```
