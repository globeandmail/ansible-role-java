# java

Role to install java. Currently the role tested on Ubunty 14.04 and installes oracle-java8-installer
from ppa:webupd8team/java repository.


##Role Variables

defaults/main.yml

```
java:
 version: oracle-java8-installer
```

##Example Playbook

```
- hosts: servers
  roles:
     - java
```

##License

MIT

##Author Information

Tal Lannder
