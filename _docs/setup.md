## local sites

"""
name: hanione_vastwhite
user:
password:
email:
"""

## files

### /_docs
> `setup.md`

### /_env

> `vendor/`

> `.env`

> `.env.exmaple`

### /

> `.gitignore`

```
wp-admin/
wp-includes/

plugins/
uploads/
themes/twentytwentyfour/

wp-config.php
wp-settings.php

# secret
.env
vendor/

# mac
# find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch
*.DS_Store
```

## github

```sh
cd "/Users/youchan/Local Sites/hanionevastwhite/app/public"

github -e pushRepo -u jnjsoftko -n wp_hanione_vastwhite -d "태백 한의원(wordpress)"
```
