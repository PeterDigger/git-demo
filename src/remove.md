# Is it tedious to remove git on my system?

No, `git` doesn't left anything after you delete a folder (for example in this case we will delete the `RBS` folder).

Generally, Windows applications are known for leftover files after uninstall. But for `Git`, it doesn't have any leftover files after delete.

> How to git works as it uses configuration per working repository on local machine.

Each working repository in the local machine will have the hidden folder called `.git`. This folder stores all the crucial data such as (remote link, branches, commit message and etc) for the local machine. Once that folder was deleted, `Git` will loses all the information of the working repository. Therefore, any configurations will be stored inside the each working repository and if one tries to execute git command without `.git` folder will return errors.

## Verdict

> Safe to say, uninstall `Git` from the control panel will leave nothing.
