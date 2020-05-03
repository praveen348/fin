# Rasa Bot Banking

A context-based chat bot for a banking client built using the Rasa stack.

## Requirements

- python=3
  - rasa

## Usage

- Install the required Python dependencies.

```bash
pip install rasa
```

- Clone this repository to a directory of your choice.

```bash
git clone https://github.com/ptanmay143/rasa-bot-banking.git
cd rasa-bot-banking
```

- Run the program.

```bash
rasa train
rasa run --cors * --endpoints endpoints.yml --log-file .\logs\out.log
```

- Run the website/index.html file to access the chat bot widget.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
