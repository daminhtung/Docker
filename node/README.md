# How to implement auto deploy to VPS(Ubuntu 20.04) use Github Action

## 1. Create su user

### 1.1 Add new User

```
~# adduser example_user
Adding user `example_user' ...
Adding new group `example_user' (1002) ...
Adding new user `example_user' (1002) with group `example_user' ...
Creating home directory `/home/example_user' ...
Copying files from `/etc/skel' ...
New password: 
Retype new password: 
passwd: password updated successfully
Changing the user information for example_user
Enter the new value, or press ENTER for the default
	Full Name []: TestUser
	Room Number []: 
	Work Phone []: 
	Home Phone []: 
	Other []: 
Is the information correct? [Y/n] Y
```

### 1.2 Add user to sudo group

```
usermod -aG sudo example_user
```

TBD
