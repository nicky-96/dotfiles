# My DotFiles

## 0. Generate `ssh` keys

Check out [Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

### Steps

```ssh
> ssh-keygen -t rsa -b 4096 -C "nicogolan7@gmail.com"
> bash
> eval "$(ssh-agent -s)"
> fish
> ssh-add ~/.ssh/id_rsa2
> sudo apt-get install xclip
> xclip -sel clip < ~/.ssh/id_rsa.pub
```

Finally [Add the ssh key to your GitHub account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account)

## 1. How to install

Follow this steps

```sh
> cd ~/projects
> git clone https://github.com/nicky/dotfiles.git
> cd dotfiles
> cp ./gitconfig ~/.gitconfig
>
```
