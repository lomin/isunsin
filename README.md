# isunsin
Commands and coordinates command line interfaces that are based on Git.
## Installation ##
Clone this repository and call
```bash
isunsin
```
Then continue with **Usage** *OR* 1-step-install with [sagwassi](https://github.com/lomin/sagwassi):
```bash
bash <(echo "all_args='git_url=https://github.com/lomin/sagwassi.git git_branch=lomin \
sagwassi_dir=/tmp/install_isunsin sagwassi_reinstall=true ansible_tags=isunsin ansible_flags=-vv'" \
&& curl -s https://raw.githubusercontent.com/lomin/sagwassi/master/sagwassi)
```
## Usage ##
Edit ~/.isunsin/config, e.g.
```
cli_sh=sagwassi;cli_home_var=sagwassi_dir;git_url=https://github.com/lomin/sagwassi.git;git_branch=master;ansible_flags=-vv
cli_sh=sagwassi;cli_home_var=sagwassi_dir;git_url=https://github.com/lomin/sagwassi.git;git_branch=lomin;ansible_skip_tags=sagwassi;ansible_flags=-vv
```
Then call
```bash
isunsin
```
# About
Admiral I Sunsin (Romanization: Yi Sun-sin; Revised Romanization: I Sunsin; Korean: 이순신; Hanja: 李舜臣; April 28, 1545 – December 16, 1598) was a Korean admiral and military general, who led the Korean naval forces during the Imjin War between 1592 and 1598 and made a decisive contribution to the defence against the Japanese invasion.
