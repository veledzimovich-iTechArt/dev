# configs

Code

codesetup

flake8

gitignore

requirements.txt

sourcery.yaml

# Setup VS Code

- manually
```bash
# Open VS Code terminal (ctrl+shift+`)
curl -L https://github.com/veledzimovich-iTechArt/dev/archive/refs/heads/master.zip --output dev-master.zip
unzip dev-master.zip
# setup global settings
cp dev-master/Code/settings.json ~/Library/Application\ Support/Code/User/
# setup project settings
cp -r dev-master/Code/.vscode .
cp dev-master/gitignore .gitignore
cp dev-master/flake8 .flake8
cp dev-master/sourcery.yaml .sourcery.yaml
rm -rf dev-master/
rm -rf dev-master.zip
```
- automatically
```bash
./codesetup
```
