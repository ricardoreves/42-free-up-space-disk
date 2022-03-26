# 42 Free Up Space Disk

## 🪧 Overview
This bash script allows you to free up to 3GB of disk space in your home directory, by deleting the cache of several applications.

## 🚀 Getting Started
1. Clone the project
```
git clone git@github.com:ricardoreves/42-free-up-space-disk.git
```
2. Navigate to the project directory
```
cd 42-free-up-space-disk
```
3. Set the script executable permission
```
chmod +x free_up_space_disk.sh
```
4. Run the script 
```
bash free_up_space_disk.sh
```
5. Run the script every time you log in. 
```
echo "bash ~/42-free-up-space-disk/free_up_space_disk.sh" >> ~/.zshrc
```

## 💡 Other Solutions

### Find and delete manually
1. Navigate to your home directory
```
cd ~
```
2. Display the total disk usage size of the directory
```
du -cksh *
```
3. Manually delete the files you deem unnecessary
```
rm -rf <path>
```

### Use machine disk (goinfre)
1. Navigate to your goinfre
```
cd /goinfre/<login42>
```
NOTE: however you will have to work on the same machine

## 🧼 Formatting the Home directory
1. Save the contents of your home in a USB key
2. Create a `.reset`/`.reset_library` file at the root of your home
```
# reset the home directory
touch ~/.reset

# reset the home library directory
touch ~/.reset_library
```
3. `Logout` then `Login`
4. Now your home is like the first day !

## :books: References
- [osxdaily.com](https://osxdaily.com/2007/03/20/command-line-disk-usage-utilities-df-and-du/) - Command Line Disk Usage Utilities: df and du
