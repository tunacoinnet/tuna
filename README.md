<h1 align="center"> TUNACOIN Node</h1>


## 🚀️ Getting started

A quick introduction of the minimal setup you need to get a running node. 

*Prerequisites:*
- - `tuna-all*.jar` and `tuna.conf` files from [releases](https://github.com/tunacoinnet/tuna/releases) 

Linux systems:
```bash
sudo apt-get update
sudo apt-get install openjdk-11-jre
java -jar node/target/tuna-all*.jar path/to/config/tuna.conf
```

Mac systems (assuming already installed homebrew):
```bash
brew cask install adoptopenjdk/openjdk/adoptopenjdk11
java -jar node/target/tuna-all*.jar path/to/config/tuna.conf
```

Windows systems (assuming already installed OpenJDK 11):
```bash
java -jar node/target/tuna-all*.jar path/to/config/tuna.conf
```
