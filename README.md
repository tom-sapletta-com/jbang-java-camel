# jbang-java-camel
Start examples with jbang for wiritng java scripts for apache camel

## install java on fedora 

```
dnf install java-devel
```

## install java with jbang

```
curl -Ls https://sh.jbang.dev | bash -s - app setup
```

```bash
jbang version
```


## config

```bash
jbang jdk home
```

```bash
jbang jdk list
```


```bash
jbang jdk install 17
jbang jdk default 17
```

## test java

create file
```bash
jbang init hello.java
```

run
```bash
jbang --java 8 hello.java
```

### shell client

```bash
jbang init -t cli hellocli.java
```

run
```bash
jbang hellocli.java
```
