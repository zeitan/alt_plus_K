# alt+K
Simple bash script to emulate in Linux/zsh the cmd +  K from macOS/OSX 
![image](https://user-images.githubusercontent.com/245020/161075879-7fe677f2-2b63-4197-b176-f19436d8d521.png)


1. Create a bash file with this content
````
echo -e '\0033\0143'
````
2. Give execution permissions to the file (````chmod +x````)
3. Add in your .zshrc/.zshprofile the following entry
````
bindkey -s '<code_keys>' '/path/to/your_file.sh\n'
````
You can use ```` showkey -a ```` to get the code_keys value


https://user-images.githubusercontent.com/245020/160969420-97b4081b-e32c-4024-ab5e-385ad71e2bb3.mp4




