# KL-Neovim

![2025-01-02_15-50](https://github.com/user-attachments/assets/bb2b7be2-c00a-4ac1-ac7c-0b12d0e6d335)


![2025-01-05_15-52](https://github.com/user-attachments/assets/7077a408-5250-464d-abe3-24143a69401e)






- If you already have Neovim installed. Backup current neovim configuration files.

```sh
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

1. **Clone the repository**

```sh
git clone https://github.com/sofijacom/KL-Neovim.git ~/.config/nvim
```

2. **Install**
```bash
# open terminal and type
cd ~/.config/nvim
chmod +x install.sh
./install.sh
```
   
- Wait until the required components are installed

## Usage
After running the install.sh script, you can start Neovim by typing nvim in your terminal.The plugins should be installed and ready to use.
