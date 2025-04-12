# System requirements
```sh
            .-/+oossssoo+\-.               
        ´:+ssssssssssssssssss+:`           ---------------- 
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 24.04.1 LTS x86_64 
    .ossssssssssssssssssdMMMNysssso.       Host: Micro-Star International Co., Ltd. MAG Z690 TOMAHAWK WIFI (MS-7D32) 
   /ssssssssssshdmmNNmmyNMMMMhssssss\      Kernel: 6.11.0-21-generic 
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 45 mins 
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss\    Packages: 3251 (dpkg), 119 (nix-user), 11 (snap) 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 5.2.37 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1920x1080, 1920x1080 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   DE: Unity 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   WM: Mutter 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   WM Theme: Adwaita 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Theme: Yaru-dark [GTK2/3] 
 \sssssssshNMMMyhhyyyyhdNMMMNhssssssss/    Icons: Yaru [GTK2/3] 
  +sssssssssdmydMMMMMMMMddddyssssssss+     Terminal: vscode 
   \ssssssssssshdmNNNNmyNMMMMhssssss/      CPU: 12th Gen Intel i7-12700K (20) @ 5.100GHz 
    .ossssssssssssssssssdMMMNysssso.       GPU: NVIDIA GeForce RTX 3060 
      -+sssssssssssssssssyyyssss+-         GPU: Intel AlderLake-S GT1 
        `:+ssssssssssssssssss+:`           Memory: 5304MiB / 31868MiB 
            .-\+oossssoo+/-.
                                                                   
                                                                   

```
                                                                   
                                                                   


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