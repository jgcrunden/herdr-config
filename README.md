# herdr-config
Configuration for my herdr setup

## add config
```bash
mkdir -p ~/.config/herdr
cp config.toml ~/.config/herdr
```

## plugins install
```bash
herdr plugin install zackshen/herdr-workspace -y
herdr plugin install bojackduy/nvim-herdr-navigation/herdr-vim-navigator -y
```

## add herdr-workspace config

```bash
mkdir -p ~/.config/herdr/plugins/config/herdr-workspace
cp herdr-workspace-config.yaml ~/.config/herdr/plugins/config/herdr-workspace/config.yaml
```

herdr server reload-config
