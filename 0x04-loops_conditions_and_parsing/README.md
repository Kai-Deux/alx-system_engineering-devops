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

2. Write a Bash script that displays `Best School` 10 times.

## Requirements:

You must use the `while` loop (`for` and `until` are forbidden)
```
sylvain@ubuntu$ ./3-until_best_school
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

3. Write a Bash script that displays `Best School` 10 times.

## Requirements:

- You must use the `until` loop (`for` and `while` are forbidden)
```
sylvain@ubuntu$ ./3-until_best_school
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
4. Write a Bash script that displays `Best School` 10 times, but for the 9th iteration, displays `Best School` and then `Hi` on a new line.

## Requirements:

- You must use the `while` loop (`for` and `until` are forbidden)
- You must use the `if` statement
```
sylvain@ubuntu$ ./4-if_9_say_hi
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Hi
Best School
sylvain@ubuntu$ 
```
5. Write a Bash script that loops from 1 to 10 and:

- displays `bad luck` for the 4th loop iteration
- displays `good luck` for the 8th loop iteration
- displays `Best School` for the other iterations

## Requirements:

- You must use the `while` loop (`for` and `until` are forbidden)
- You must use the `if`, `elif` and `else` statements
```
sylvain@ubuntu$ ./5-4_bad_luck_8_is_your_chance
Best School
Best School
Best School
bad luck
Best School
Best School
Best School
good luck
Best School
Best School
sylvain@ubuntu$ 
```