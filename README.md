# Slack Bot YOB Calculator

Welcome to the Slack Bot YOB (Year of Birth) Calculator project! This is a simple Slack bot implemented in Go using the `slacker` library. The bot calculates your age based on the year of birth provided in a Slack command.

## Getting Started

### Prerequisites

- Go installed on your machine
- Slack App and Bot tokens

### Configuration

Set the following environment variables with your Slack Bot Token and Slack App Token:

```bash
export SLACK_BOT_TOKEN=xoxb-your-bot-token
export SLACK_APP_TOKEN=xapp-your-app-token
```
### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Mayejacob/slack-age-bot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd slack-bot-yob-calculator
    ```
3. Run the application:
    ```bash
    go run main.go
    ```
The bot will start listening for Slack commands.

## command 
```bash
@Age Bot my yob is 1997
```

### The bot will reply with your calculated age.

## Command Events

The application prints command events to the console. These events include details about each command, such as timestamp, command name, parameters, and event type.


## Acknowledgments

    [https://github.com/shomali11/slacker](slacker: A Slack client library for Go.)
    [https://github.com/AkhilSharma90/GO-Slackbot-Calculates-Age](AkhilSharma)