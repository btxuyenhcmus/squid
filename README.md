# Setup anomynouse proxy server
1. Clone source from git repository
```
$git clone https://github.com/btxuyenhcmus/squid
```

2. Install apache2-utils
```
$ sudo apt install apache2-utils
```

3. Generate password
```
$ htpasswd -c passwords <username>
```

4. Up container
```
$ docker-compose up -d
```

5. Done