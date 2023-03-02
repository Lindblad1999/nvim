# nvim
My nvim configuration


## Install Neovim
1. Go the neovim github page
2. Download the tarball file for the version you want
	1. I use 0.8.3
3. Extract folder 
```bash
tar zxvf foldername
```
4. Copy entire folder into /user/local/bin
5. Create symbolic link to bin file
```bash
ln -s nvim-linux64/bin/nvim nvim
```
Now nvim should run by using the command "nvim".


## Other stuff to do
1. Clone this entire repo into ~/.config

2. install package manager
```bash
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
 ```

3. in nvim run: 
```
:PackerSync
```
