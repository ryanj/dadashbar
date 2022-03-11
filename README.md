# da dashbar 📈

collected trello scrapings from my Dev Rel team

## Setup

Init a python virtual environment and source your deps

  ```bash
  virtualenv -p python3.10 env
  source ./env/bin/activate
  pip install -r requirements.txt
  ```

## Config

Export your trello API keys (from [trello.com/app-key](https://trello.com/app-key))
  
  ```bash
  export TRELLO_API_KEY="..."
  export TRELLO_API_SECRET="..."
  export TRELLO_TOKEN="..."
  ```

## Run

Boot the server

```bash
python app.py
```

Take a pull from flask at [localhost:8080](http://localhost:8080)
