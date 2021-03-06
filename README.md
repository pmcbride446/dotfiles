#Usage

Clone the repo into your home directory:

```shell
cd ~
git clone https://github.com/pmcbride446/dotfiles.git
```

Then execute the symlink script from the new dotfiles directory:

```shell
cd ~/dotfiles
./symlink_dotfiles.sh
```

Edit the content of `.user_variables` and `.user_gitconfig` in the dotfiles directory to store sensitive user variables and keys:

```shell
# EXAMPLE .user_variables 
export KEY=value
```
```shell
# EXAMPLE .user_gitconfig
[user]
  name = "Your Name"
  email = user@email.com
```

====

If using homebrew on Mac OSX:

First update Homebrew install Brewdler..

```shell
brew update
gem install brewdler
```

Then run brewdle install in the same directory as your `Brewfile`

```shell
cd ~/dotfiles
brewdle install
```
