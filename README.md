# handy_note

## DB

Use navicat11 client to connect localhost mysql database and get 
`Client does not support authentication protocol requested by server; consider upgrading MySQL client`

```
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'newpass';
```

## IDE

idea2018 active code

```
http://idea.lanyus.com/
```

## Maven 

### 环境变量

```
vim ~/.bash_profile
export M2_HOME=/Users/username/Documents/maven #这里是你maven的路径
export PATH=$PATH:$M2_HOME/bin
source ~/.bash_profile

mvn -v
```

### 插件使用

- [maven-install-plugin](http://maven.apache.org/plugins/maven-install-plugin/usage.html)
- [maven-install-plugin/examples](http://maven.apache.org/plugins/maven-install-plugin/examples/specific-local-repo.html)
