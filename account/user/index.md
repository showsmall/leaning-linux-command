用户相关命令
=========



### 列出所有用户

	cat /etc/passwd

输出如下:

    [root@localhost ~]# cat /etc/passwd
    root:x:0:0:root:/root:/bin/bash
    bin:x:1:1:bin:/bin:/sbin/nologin
    daemon:x:2:2:daemon:/sbin:/sbin/nologin
    adm:x:3:4:adm:/var/adm:/sbin/nologin
    lp:x:4:7:lp:/var/spool/lpd:/sbin/nologin
    sync:x:5:0:sync:/sbin:/bin/sync
    shutdown:x:6:0:shutdown:/sbin:/sbin/shutdown
    halt:x:7:0:halt:/sbin:/sbin/halt
    mail:x:8:12:mail:/var/spool/mail:/sbin/nologin
    uucp:x:10:14:uucp:/var/spool/uucp:/sbin/nologin
    operator:x:11:0:operator:/root:/sbin/nologin
    games:x:12:100:games:/usr/games:/sbin/nologin
    gopher:x:13:30:gopher:/var/gopher:/sbin/nologin
    ftp:x:14:50:FTP User:/var/ftp:/sbin/nologin
    nobody:x:99:99:Nobody:/:/sbin/nologin
    vcsa:x:69:69:virtual console memory owner:/dev:/sbin/nologin
    saslauth:x:499:76:"Saslauthd user":/var/empty/saslauth:/sbin/nologin
    postfix:x:89:89::/var/spool/postfix:/sbin/nologin
    sshd:x:74:74:Privilege-separated SSH:/var/empty/sshd:/sbin/nologin
    mysql:x:27:27:MySQL Server:/var/lib/mysql:/bin/bash
    nginx:x:498:499:nginx user:/var/cache/nginx:/sbin/nologin
    jenkins:x:497:498:Jenkins Continuous Integration Server:/var/lib/jenkins:/bin/false
    postgres:x:26:26:PostgreSQL Server:/var/lib/pgsql:/bin/bash
    dolphin-ci_doc:x:500:500::/home/dolphin-ci_doc:/bin/bash

第一个字段是用户的login name.





### 参考资料

- [Users and Groups in Linux](http://blog.csdn.net/Graveworm/article/details/5696634)
