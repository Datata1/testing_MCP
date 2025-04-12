1. install n8n (usr/local/bin/n8n)
```sh
npm i n8n -g
```

2. install process-compose (/home/user/.local/bin/process-compose)
```sh
sh -c "$(curl --location https://raw.githubusercontent.com/F1bonacc1/process-compose/main/scripts/get-pc.sh)" -- -d -b ~/.local/bin
```

3. install ollama (/usr/local/bin/ollama)
```
curl -fsSL https://ollama.com/install.sh | sh
```

3.1 pull model 
```sh
ollama pull phi4
```
or any other model listed [here](https://ollama.com/library)

4. install python packages
```
uv sync
```

5. start process-compose
```
process-compose
```