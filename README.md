# git-crypt-instruction

```
brew install git-crypt

git-crypt init 
    git-crypt stores the generated key in the file .git/git-crypt/keys

echo "private.yml filter=git-crypt diff=git-crypt" > .gitattributes

```