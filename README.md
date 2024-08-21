# Kotlin app
## Client application in Kotlin using Ktor framework, which allows to send messages to Discord platform.

## Discord
1. Go to the server settings.
2. Navigate to Integrations -> Webhooks.
3. Create new webhook or copy the url of existing one.

## Set environmental variable
### Replace with url you previously copied and run:
Windows:
```bash
set DISCORD_WEBHOOK_URL=https://discord.com/api/webhooks/{webhook_id}/{webhook_token}
```
Linux:
```bash
export DISCORD_WEBHOOK_URL="https://discord.com/api/webhooks/{webhook_id}/{webhook_token}"
```

## Run in terminal:
```bash
./gradlew build
./gradlew run
```
