VPS Command

```
bash <(curl -s https://raw.githubusercontent.com/DevrdxDev/VPS-Ptero/refs/heads/main/VPS)
```                                                                                 

Pterodactyl Command

```
bash <(curl -s https://raw.githubusercontent.com/DevrdxDev/VPS-Ptero/refs/heads/main/Pterodactyl)
```

```
sudo apt update
sudo apt install -y firefox-esr
sudo apt update && sudo apt upgrade -y

sudo apt install xfce4 xfce4-goodies xrdp -y

echo "startxfce4" > ~/.xsession
sudo chown $(whoami):$(whoami) ~/.xsession


sudo systemctl enable xrdp
sudo systemctl restart xrdp
```

VM Machine Command

```
bash <(curl -fsSL https://raw.githubusercontent.com/DevrdxDev/VPS-Ptero/refs/heads/main/vm.sh)
```
