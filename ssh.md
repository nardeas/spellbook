# SSH

## Multi-hop file transfer

```
scp -o ProxyCommand="ssh <remote user>@<remote server 1> nc <remote server 2> 22" <local file path> <remote user>@<remote server 2>:<remote file path>
```
