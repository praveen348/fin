# Rasa Bot Banking

> Context-based chat bot for a banking portal

## Instructions

### Setup

- Install [Git-SCM](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

- Clone this repository and change directory to the cloned folder.

  ```powershell
  git clone https://github.com/ptanmay143/rasa-bot-banking.git
  Set-Location .\rasa-bot-banking\
  ```

- Install [Miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Create a new conda environment with the name `rasa-bot-banking` using Python v3.7 and install the required dependencies.

  ```powershell
  conda create -n rasa-bot-banking python=3.7
  ```

- Activate the conda environment and install the pip dependencies.

  ```powershell
  conda activate rasa-bot-banking
  pip install rasa
  ```

  > Follow [Rasa Installation Guide](https://rasa.com/docs/rasa/user-guide/installation/) for more help.

### Usage

- Activate the conda environment.

  ```powershell
  conda activate rasa-bot-banking
  ```

- Train the NLU model.

  ```powershell
  rasa train
  ```

- Start the Rasa server.

  ```powershell
  rasa run --cors * --endpoints endpoints.yml --log-file .\logs\out.log
  ```

- Open `website/index.html` in a web browser to access the chat bot widget.
