# TASKS
0. Read for this task:

    - Linux and Mac OS users
    - Windows users
# man: `ssh-keygen`

You will soon have to manage your own **servers** concept page hosted on remote `data centers.` We need to set them up with your RSA public key so that you can access them via SSH.

Create a RSA key pair.

## Requirements:

- Share your **public key** in your answer file `0-RSA_public_key.pub`
- Fill the `SSH public key` field of your `intranet profile` with the public key you just generated
- **Keep the private key to yourself in a secure location**, you will use it later to connect to your servers using SSH. Some storing ideas are Dropbox, Google Drive, password manager, USB key. Failing to do so will prevent you to access your servers, which will prevent you from doing your projects
- If you decide to add a passphrase to your key, make sure to save this passphrase in a secure location, you will not be able to use your keys without the passphrase
SSH and RSA keys will be covered in depth in a later project.

1. Write a Bash script that displays `Best School` 10 times.

## Requirement:

- You must use the `for` loop (`while` and `until` are forbidden)

```
sylvain@ubuntu$ head -n 2 1-for_best_school 
#!/usr/bin/env bash
# This script is displaying "Best School" 10 times
sylvain@ubuntu$ ./1-for_best_school 
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
sylvain@ubuntu$ 
```
**Note that:**

- The first line of my Bash script starts with `#!/usr/bin/env bash`
- The second line of my Bash scripts is a comment explaining what it is doing