TODO

to run:
1. create a `config.json` using `config.example.json` as a template (remember to set to correct registry)
2. `chmod ./link-tool +x`
3. run `./link-tool link` to interconnectedly link modules
4. run `./link-tool status` to cross check if the version of target modules match the version specified in package.json of all modules

TIPS:
to checkout a certain release of a library:
```
cd LibraryFolder
git tag
git checkout [TARGET TAG]
```
