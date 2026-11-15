# SSH

Scripts and configuration for connecting to a server with SSH keys.

| File | Description |
|------|-------------|
| `0-use_a_private_key` | Connects to the server as `ubuntu` using the private key `~/.ssh/school` |
| `1-create_ssh_key_pair` | Creates a 4096-bit RSA key pair named `school`, protected by a passphrase |
| `2-ssh_config` | SSH client configuration: uses `~/.ssh/school` and refuses password authentication |
