# post-commit-to-telegram
Notify user about commit being pushed to remote repository

1. Update TELEGRAM_KEY and TELEGRAM_CHAT_ID https://core.telegram.org/bots
2. Put the `post-receive` file in `.git/hooks` in you **REMOTE** repository
3. You should receive notification when someone pushes into the repository
