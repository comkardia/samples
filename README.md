# samples
This repository contains sample assets for testing the various algorithms developed as part of the ComKardia software application

## Setup repository
### For Windows

If you are a Window's user, clone this repository at the root of the `C:/` drive.

```bash
cd C:
git clone https://github.com/comkardia/samples.git
```

After cloning the repository, you need to set the following environment variable.

```bash
SAMPLES_DIR=C:\samples
```

The name of the environment variable is `SAMPLES_DIR` and the value of the variable is `C:\samples`. 

**Note:** Make sure you add this environment variable to both the user profile as well as the system profile.

### Linux & macOS

If you are a Unix user (Linux & macOS), clone this repository at the root of your home folder.

```bash
cd ~
git clone https://github.com/comkardia/samples.git
```

After cloning the repository, you need to set the following environment variable.

```bash
SAMPLES_DIR=~/samples
```

The name of the environment variable is `SAMPLES_DIR` and the value of the variable is `~/samples`. If you know the complete path, then expand the value of `~` to its's full value.

**Note:** If you are using `bash` as your preferred shell, make sure you add this environment variable to both .bashrc and .bash_profile

```bash
echo "export SAMPLES_DIR=~/samples" >> .bashrc
echo "export SAMPLES_DIR=~/samples" >> .bash_profile
```

**Note:** If you are using `zsh` as your preferred shell, make sure you add this environment variable to both .zshrc and .zprofile

```bash
echo "export SAMPLES_DIR=~/samples" >> .zshrc
echo "export SAMPLES_DIR=~/samples" >> .zprofile
```
