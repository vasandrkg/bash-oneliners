# Force to use password and not ssh-key to connect to host
```sh
ssh -o PreferredAuthentications=password -o PubkeyAuthentication=no some_user@some_host;
```

# Provide pathword on the command line
```sh
sshpass -p "some_pass" ssh -o PreferredAuthentications=password -o PubkeyAuthentication=no some_user@some_host;
```

# Provide pathword from the text file
```sh
sshpass -f ~/.ssh/some_file_with_pathword.txt ssh -o PreferredAuthentications=password -o PubkeyAuthentication=no some_user@some_host;
```

