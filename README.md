# dotfiles with  MACOS

The script dotfile change and add files;`.bash_aliases`,`.bash_profile`,`.bash_prompt`,`.bashrc`,`.gitconfig`,`.exports`.

**Warnings** Don’t blindly use my settings unless you know what that entails.

## Installation 🧰

Need Install Homebrew before use:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### First usage. Using Git and deploy the script with:

```bash
git clone https://github.com/airqz/dotfiles.git && cd dotfiles && source bootstrap.sh
```

### Or to update the script:

To update you MacOS, `cd` into your local `dotfiles` repository and then:

```bash
source bootstrap.sh
```

## Configuration ⚙️

Change in `.gitconfig`:
```bash
[user]
    name = ADDYOURNAME
```
