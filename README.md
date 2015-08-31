# rad
Pull &amp; push system configuration files

## Usage

```
cd configs
git init .
mkdir -p hosts/alpha
mkdir -p hosts/beta
rad_pull_files alpha

rad_push_files alpha -f


sh rad/pull-all

sh rad/push-all -f

sh rad/update-all
```
