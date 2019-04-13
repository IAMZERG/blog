---
layout: post
title: "A Foray into the Internet of Things - Hardening the Server"
authors: Wes
date: "2019-04-13 11:53:05 -0500"
en: true
comments: true
---

# Hardening the Server

So, I have the email server set up.  I already have an IPtables config that is fairly strict, and I have a pretty neat setup overall. Next step is finishing the ssh setup:

```
ssh-keygen -f ~/.ssh/name-of-keyfile -t rsa -b 2048
```

Next, copy the key using ssh-copy-id (or do so manually):
```
ssh-copy-id -i ~/.ssh/key-file-name-here user@host
```
OR

```
# if the file doesn't exist
mkdir -p ~/.ssh && touch ~/.ssh/authorized_keys
chmod 700 ~/.ssh && chmod 600 ~/.ssh/authorized_keys

(open file in vi/vim/nano, paste key into file)
```

After I have SSH keys set up on all the computers I use regularly, I will disable password authentication for SSH.  Then, it's just a matter of adding a domain name, and I'll be able to access webmail remotely with little effort.
