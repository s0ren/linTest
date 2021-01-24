Linux core

```bash
echo "# linTest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/s0ren/linTest.git
git push -u origin main
```


```bash
git remote add origin https://github.com/s0ren/linTest.git
git branch -M core
git push -u origin core
```

For at lave en ny maskine (megaServer), med en ny branch (megaServer):
```bash
git init
git branch -M  megaServer
git remote add origin https://github.com/s0ren/linTest.git
git push -u origin megaServer
```
