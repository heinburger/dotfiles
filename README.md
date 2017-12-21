# Steven's dotfiles
forked from https://github.com/mathiasbynens/dotfiles

### Using Git and the bootstrap script

```bash
git clone https://github.com/heinburger/dotfiles.git && cd dotfiles && source bootstrap.sh
```

To update, `cd` into your local `dotfiles` repository and then:

```bash
source bootstrap.sh
```

Alternatively, to update while avoiding the confirmation prompt:

```bash
set -- -f; source bootstrap.sh
```
