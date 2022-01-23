# 42-free-up-space-disk
🧹Free up space in your disk 42

## Usage
### Manually
```
git clone 
cd 42-free-up-space-disk
chmod +x free_up_space_disk.sh
bash free_up_space_disk.sh
```

### Automatically
run the script on every startup
Open `vim ~/.zshrc` and add the command below at the end of the file, this will run the script every time you log in. 
```
bash ~/42-free-up-space-disk/free_up_space_disk.sh
```
