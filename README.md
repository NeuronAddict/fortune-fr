# fortune-fr
Citations francaises de grands hommes pour fortune.

**Ce dépot est consacré à des citations françaises**

## Installation pour fortune

```
sudo apt install fortune cowsay
git clone https://github.com/NeuronAddict/fortune-fr
sudo mkdir -p /usr/share/games/fortunes/fr
sudo cp -r fortune-fr/grands-hommes-politiques /usr/share/games/fortunes/fr/
sudo strfile /usr/share/games/fortunes/fr/grands-hommes-politiques/*
echo 'fortune rands-hommes-politiques | cowsay' >> ~/.bashrc
```
