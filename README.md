###SETUP STEPS


- install uv in your machine
  `curl -LsSf https://astral.sh/uv/install.sh | sh`
  
  
- then pull the repo and go to stream_store_kafka dir

- run `uv sync`

- create venv -> `uv venv`

- activate venv -> source .venv/bin/activate

- `docker compose up`

- `uv run stream-store-kafka` to run producer file

- `uv run python -m stream_store_kafka.tracker` to run tracker file
