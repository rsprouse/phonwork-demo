# phonwork-demo
Demo of phonwork with submodules

## Adding submodules

Examples of adding submodules:

```bash
git submodule add https://github.com/rsprouse/phonwork-db_mri assets/db_mri
git add .gitmodules
git add assets/db_mri
git commit -m 'Added db_mri assets'

git submodule add https://github.com/rsprouse/phonwork-mg_mri assets/mg_mri
git add .gitmodules
git add assets/mg_mri
git commit -m 'Added mg_mri assets'
```

Note that pointers to these submodule repos are to specific versions, as indicated by the SHA, which you can see on github with the `@ SHA`:

![Screenshot of submodule with SHA](assets/submodule_sha.png)

On your local filesystem these directories will just be `db_mri` and `mg_mri`; the `@ SHA` will not be part of the directory names.

