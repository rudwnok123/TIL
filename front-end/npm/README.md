# NPM
## NPX
__Using packages without install__
```
$ cowsay
-bash: cowsay: command not found
$ npx cowsay "Hello, NPX"
# Using directly package without install is possible!
npx: installed 5 in 16.991s
 ____________
< Hello, NPX >
 ------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

## Publish scoped package
__package.json__
```
{
  "name": "@SCOPE/PACKAGE_NAME",
  ...
}
```

If want to publish this to public, add this.
```
"publishConfig": {
  "access": "public"
}
```
