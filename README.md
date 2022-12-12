# README

## Usage
```bash
## clone project
git clone git@github.com:uyaki/blog.git

## update theme
cd blog
git submodule init 
git submodule update

## pull public
cd public
git pull
cd ..
```

## update

### Add A new content

```bash
hugo new post/[modules]/[title].md

hugo

hugo server -D
## 127.0.0.1:1313
```

### push

```bash
## push public
cd public 
git add .
git commit -m ""
git push
## push blog
cd ..
git add .
git commit -m ""
git push
```
