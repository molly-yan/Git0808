# git


## inbound file


### git add *
![](https://images-na.ssl-images-amazon.com/images/I/81JsQZ4OynL._AC_SL1500_.jpg)


``` sh
git init

git status

# get all files on the wagon
git add *

# move the wagon into our repository
git commit -m"init"

```

## update file

### view out door
``` sh
git status
```

### view the diff

``` sh
git diff
```


## log

### view log

``` sh
git log
```

```

commit 4b22b14723e8c4f932bcc024da2c5024d3df4768 (HEAD -> master)
Author: mike.xie <mike.xie@me.com>
Date:   Sat Aug 8 21:51:42 2020 +0800

    append image

commit 85a882922ae2fd670d4de3d85135e230a4ccfa7c
Author: mike.xie <mike.xie@me.com>
Date:   Sat Aug 8 21:47:48 2020 +0800

    init
``` 

### go to the past

``` sh
git checkout 85a882922ae2fd670d4de3d85135e230a4ccfa7c
```


### back to future
``` 
git checkout master
```

全部删除：git add -A
删除部分：git add *.md
