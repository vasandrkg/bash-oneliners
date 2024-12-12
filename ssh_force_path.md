# Force to use password and not ssh-key

```bash
ssh -o PreferredAuthentications=password -o PubkeyAuthentication=no some_user@some_host;
```
