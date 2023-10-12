# blip-finetune

BLIP Finetuning from eeshashetty [https://github.com/eeshashetty/captionary-api]

## Setup

1. Create a virtual environment and install the requirements

```bash
python3.11 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

2. Setup a [wandb](https://wandb.ai/) account and make a note of your API key, project name (can create a new one) and entity name (your username if not part of a team)

3. Create a `.env` file and modify the values with your wandb information

```bash
cp .env.example .env
```

