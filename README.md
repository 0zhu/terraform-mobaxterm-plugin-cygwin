# Terraform plugin for MobaXterm and Cygwin <a href="https://github.com/zhubanRuban/terraform-mobaxterm-plugin-cygwin"><img height="30" src="https://camo.githubusercontent.com/7710b43d0476b6f6d4b4b2865e35c108f69991f3/68747470733a2f2f7777772e69636f6e66696e6465722e636f6d2f646174612f69636f6e732f6f637469636f6e732f313032342f6d61726b2d6769746875622d3235362e706e67"></a> <a href="https://mobaxterm.mobatek.net/" target="_blank"><img align="right" height="40" src="https://mobaxterm.mobatek.net/img/moba/xterm_logo.png"></a> <a href="https://www.terraform.io/" target="_blank"><img align="right" height="40" src="https://www.refactr.it/wp-content/uploads/2019/10/Terraform_logo_256_256.png"></a>

Created from [Terraform release for Windows 32-bit](https://www.terraform.io/downloads.html).

# [How to install](https://mobaxterm.mobatek.net/plugins.html)

> In order to install plugin, just download [.mxt3](https://github.com/zhubanRuban/terraform-mobaxterm-plugin-cygwin/raw/master/terraform_0.12.21.mxt3) file and put it in the same directory than MobaXterm executable.

## Cygwin users can also install the plugin:

### Cygwin x86

```
wget -qO mtr https://github.com/zhubanRuban/terraform-mobaxterm-plugin-cygwin/raw/master/terraform_0.12.21.mxt3 && unzip mtr -d / && rm -f mtr
```

### Uninstallation

```
wget -qO mtr https://github.com/zhubanRuban/terraform-mobaxterm-plugin-cygwin/raw/master/terraform_0.12.21.mxt3 && unzip -Z1 mtr | xargs -I{} rm -vf /{} && rm -f mtr
```
