# Resolve NPM Manual Audit

Source: [Stackkoverflow - How do I fix a vulnerable NPM Package?](https://stackoverflow.com/questions/50328324/how-do-i-fix-a-vulnerable-npm-package-in-my-package-lock-json-that-isnt-listed)

TLDR: Update the parent package using: `[npm i $PARENT_PKG_NAME]`

When updating dependencies, you should review the CHANGELOG for any breaking changes.

## Diagnosis

`[npm audit]` will reveal both the vulnerable package (note that you'll need a package-lock.json file for this, so you'll need to `[run npm i]`), as well as the package that it is a dependency of (if applicable). Note that you can also use `[npm ls $CHILD_PKG_NAME]` to see its parent dependencies.

## Quick Fix Attempt

`[npm audit fix]` and `[npm audit fix --force]` are worth a try, but sometimes the fix will need to be done manually (see below).

## Manual Fix

Most likely the parent package will have already fixed their dependencies (you can verify this by going to their GitHub and reviewing the recent commits--or just seeing if this fixes it), so you can just run `[npm i $PARENT_PKG_NAME @$NEW_VERSION]` and it will update your package-lock.json.

If parent has not fixed the vulnerability

If the maintainer doesn't seem to be responsive, you may consider using an alternative package that accomplishes the same thing or forking the package and updating the vulnerability yourself.

## Verify Fix

You can now verify that it worked by running `[npm audit]` and ensuring that no vulnerabilities are showing up. Commit your changes, push them to GitHub, refresh your notifications/alerts and they should be gone!
