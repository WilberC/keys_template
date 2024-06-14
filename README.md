<h2 align="center">Keys template</h2>

- This is a simple template to be used at your [dotfiles](https://github.com/kucho/dotfiles)

## Structure

### local_git

Used for personal git credentials and more.

- `~/.local_git/.git_personal_config` this contains config directly apply to your `.gitconfig`
- `~/.local_git/.wsl2_os_specific` has the path of your 1password op-ssh for your personal machine

### local_ssh

Used for personal `ssh` configs. You can simple add `ssh` configurations to `~/.local_ssh/.general_ssh` that will be applied to osx, linux and wsl2 or you can add also specific config for each system in the corresponding file. All are referenced in the corresponding dotfiles to get the config automatically.