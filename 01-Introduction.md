# Seting up Linux environment 

  Here I used CentOS7 version as Linux distribution.

   Go through the process of setting up the necessary tools and packages for following along with this course by setting up a Linux   
   distribution for development.

### Required Software Packages, Tools, and Files
  ```
  git
  wget
  which
  words (need file at /usr/share/dict/words)
  lsof
  text editor of your choice
  python 3.6.5
```

### Installing Packages

```
  sudo su -
  $ yum update
  $ yum groupinstall -y "development tools"
  $ yum install -y \
    lsof \
    wget \
    vim-enhanced \
    words \
    which
  $ exit
```

### Configuring Git

```
  $ git config --global user.name "Your Name"
  $ git config --global user.email "your_email@example.com"
```

