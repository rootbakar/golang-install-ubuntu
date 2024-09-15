### Golang Install Ubuntu
How to install golang on ubuntu

```bash
sudo apt update -y
```

```bash
sudo apt upgrade -y
```

```bash
wget https://go.dev/dl/go1.23.1.linux-amd64.tar.gz -O go.tar.gz
```

```bash
sudo tar -xzvf go.tar.gz -C /usr/local
```

```bash
echo export PATH=$HOME/go/bin:/usr/local/go/bin:$PATH >> ~/.profile
```

```bash
source ~/.profile
```

```bash
go version
```
