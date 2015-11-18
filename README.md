#AutoGhost.sh

![](http://evil7.net/content/images/2015/11/AutoGhostLogo.jpg)

*More Awesome things in my blog ! >> [[ evil7's Blog ]](http://evil7.net)* 原谅我学传媒情不自禁做张图 :p（原图来自火熊CG网）


#Start install

**Tips :**

1. Use a new OS. that's better !

2. It will download and build a **NEW GhostBlog** at `/srv/ghost` !

3. So if you are already have one in `/srv/ghost` don't forget to **BACKUP** your Database and Themes and any important files at first !

4. Maybe some bugs with v1.0. How about check it out first ! → <a href="https://coding.net/u/LJokerP/p/AutoGhost/git/raw/master/AutoGhost.sh" target="blank">Code</a>

**Make everything clear and run :**

```
wget https://coding.net/u/LJokerP/p/AutoGhost/git/raw/master/AutoGhost.sh

sudo sh AutoGhost.sh
```

**Input your domain for your blog when you see the**

```
please input your domain :
http://
```

( It will take 1-3 mins. Depend on your internet. )

#Useful info

About GhostBlog : [ghost.org (en)](http://ghost.org) / [ghostchina.com (cn)](http://ghostchina.com)

Support OS : `Ubuntu` / `Debian (maybe work. I never try...)`

Will install : `curl` / `unzip` / `Nodejs` / `npm` / `SQLite3` / `Nginx` / `forever` / `watchdog`

All blog-files install in : `/srv/ghost`

Config file for Nginx save in : `/etc/nginx/sites-available/ghost.config`

Need help please check here : [Feedback_in_Coding](https://coding.net/u/LJokerP/p/AutoGhost.sh/topic/64657) or [Feedback_in_Mail](mailto:ljokerp@sina.com?subject=AutoGhost_feedback)

More Awesome things please check my blog ! >> [[ evil7's Blog ]](http://evil7.net)

#Versions list

* ( 2015/11/04 ) v1.0 ---- Coding AutoGhost.sh and fixed some bugs. It can't used in `curl -sL xxx | sh -` to do install. It will skip the `read -p` when running.
* ( 2015/11/10 ) v1.1 ---- Fix a little bug and now ghost suppost nodejs-0.12 so let's use 0.12. ( 11:27 Happy 1111 day! )