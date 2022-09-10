# An APT remove errors script

With this script you can use apt removing some lock errors

to use this script run:

```bash
chmod +x ./apt
sudo ./apt {apt-command}

example:
sudo ./apt install git
```

you can also change your apt by this script adding this as an alias
example:
```
chmod +x ./apt

and then add to your shell config file (as .zshrc, .bashrc, .bash_profile)
alias apt="sudo path-to-new-apt-script ${@:1}"
```
