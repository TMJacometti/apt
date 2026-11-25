# Repositório apt do TMJLite

Pacotes `tmjlite` (CLI) e `tmjstudio` (IDE) para Debian/Ubuntu, amd64.
Gerado por `scripts/publish-apt.py` do TMJPlatform — não edite à mão.

```bash
curl -fsSL https://tmjacometti.github.io/apt/tmjlite.gpg | sudo tee /usr/share/keyrings/tmjlite.gpg >/dev/null
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/tmjlite.gpg] https://tmjacometti.github.io/apt stable main" | sudo tee /etc/apt/sources.list.d/tmjlite.list
sudo apt update
sudo apt install tmjlite tmjstudio
```

Atualizar depois: `sudo apt update && sudo apt upgrade`.
