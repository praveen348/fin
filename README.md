# Rasa Bot Banking

A context-based chat bot for a banking client built using the Rasa stack.

## Requirements

- Python 3
  - rasa

## Instructions

Clone this repository.

```ps
git clone https://github.com/ptanmay143/rasa-bot-banking.git
Set-Location rasa-bot-banking
```

Train the NLU model followed by starting the Rasa server.

```ps
rasa train
rasa run --cors * --endpoints endpoints.yml --log-file .\logs\out.log
```

Run the `website/index.html` file to access the chat bot widget.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
