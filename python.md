# Python
```
sudo apt install python3 python3-pip python3-venv -y

sudo apt update && sudo apt install -y build-essential procps curl file git


```

homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

```

add homebrew

```
echo >> ~/.bashrc
echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.bashrc
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"

```
Terminal

```

- Run these commands in your terminal to add Homebrew to your PATH:
    echo >> /home/codespace/.bashrc
    echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv bash)"' >> /home/codespace/.bashrc
    eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv bash)"
- Install Homebrew's dependencies if you have sudo access:
    sudo apt-get install build-essential
  For more information, see:
    https://docs.brew.sh/Homebrew-on-Linux
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh
```

