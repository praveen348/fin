# Rasa Bot Banking

> Contextual chat bot for a banking portal

---

- [Rasa Bot Banking](#rasa-bot-banking)
  - [Instructions](#instructions)
    - [Setup](#setup)
    - [Usage](#usage)
  - [License](#license)

---

## Instructions

### Setup

- Install [Git-SCM](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

- Clone this repository and change directory to the cloned folder.

  ```shell
  git clone https://github.com/ptanmay143/rasa-bot-banking.git
  cd ./rasa-bot-banking/
  ```

- Install [Miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Create a conda environment.

  ```shell
  conda create -n rasa-bot-banking
  ```

- Install required dependencies.

  ```shell
  conda env create -f ./environment.yml
  ```

  > Follow [Rasa Installation Guide](https://rasa.com/docs/rasa/user-guide/installation/) for more help.

### Usage

- Activate the conda environment.

  ```shell
  conda activate rasa-bot-banking
  ```

- Train the NLU model.

  ```shell
  rasa train
  ```

- Start the Rasa server.

  ```shell
  rasa run --cors * --endpoints endpoints.yml --log-file ./logs/out.log
  ```

- Open `website/index.html` in a web browser to access the chat bot widget.

---

## License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
