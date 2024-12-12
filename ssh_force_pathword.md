# Force to use password and not ssh-key to connect to host

```sh
ssh -o PreferredAuthentications=password -o PubkeyAuthentication=no some_user@some_host;
```
