# git-crypt-instruction

```
brew install git-crypt

(git-crypt stores the generated key in the file .git/git-crypt/keys)
git-crypt init 

echo "private.yml filter=git-crypt diff=git-crypt" > .gitattributes

git add .gitattributes
git commit -m "Tell git-crypt to encrypt private.yml"

git add public.yml
git add private.yml

git commit -m "Add public.yml and private.yml"
git push origin main
```

```
git-crypt unlock .git/git-crypt/keys/default 
```