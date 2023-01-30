### Linux UBUNTU-18.04-SERVER

Ferramenta CLI interativa para instalar e atualizar whaticket

Preparado para instalação em um servidor local 

### Download & Setup

Em primeiro lugar, você precisa baixá-lo:


```bash
sudo apt -y update && apt -y upgrade
sudo apt install -y git
git clone https://github.com/cicerosz/whaticket-installer.git
```

Agora, tudo o que você precisa fazer é torná-lo executável:

```bash
sudo chmod +x ./whaticket-installer/whaticket
```

### Execução

Depois de baixar e torná-lo executável, você precisa **navegar para** o diretório do instalador e **executar o script com sudo**:

```bash
cd ./whaticket-installer
```

```bash
sudo ./whaticket
```
