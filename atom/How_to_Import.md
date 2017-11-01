### Export the packages.list
apm list --installed --bare > package-list.txt

### Import the packages.list
apm install --packages-file package-list.txt
