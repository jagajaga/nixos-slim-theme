#Theme for [SLiM](http://slim.berlios.de/) with [NixOS](http://nixos.org/) thematics HiDPI version.
![preview](https://github.com/jagajaga/nixos-slim-theme/raw/master/preview.png)

## How to use

To use this slim theme in NixOS you set the `theme` option, like so:

```
  slim = {
    enable = true;
    theme = pkgs.fetchurl {
      url    = "https://github.com/jagajaga/nixos-slim-theme/archive/Final.tar.gz";
      sha256 = "4cab5987a7f1ad3cc463780d9f1ee3fbf43603105e6a6e538e4c2147bde3ee6b";
    };
  };
```

Then you need to do `nixos-rebuild switch` and restart slim to apply the theme.
