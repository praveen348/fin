# Rasa Bot Banking

Context-based chat bot for a banking client

## Description

This chat bot was built using the Rasa stack and Python 3.

## Requirements

- Python 3
  - rasa

## Instructions

Train the NLU model followed by starting the Rasa server.

```ps
rasa train
rasa run --cors * --endpoints endpoints.yml --log-file .\logs\out.log
```

Run `website/index.html` to access the chat bot widget.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
