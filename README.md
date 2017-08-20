# owasp-mutillidae
This is a docker image containing OWASP Mutillidae

This docker image is based on https://registry.hub.docker.com/u/tutum/lamp/

Pull image:
```docker pull feltsecure/owasp-mutillidae```

Start with random mysql password:
```docker run -d -p 80:80 feltsecure/owasp-mutillidae```

[Tutum Lamp Image](https://registry.hub.docker.com/u/tutum/lamp/ "Tutum Lamp Image") allows you to set MYSQL password as an environment variable:

```docker run -d -p 80:80 -p 3306:3306 -e MYSQL_PASS="SecretPass" feltsecure/owasp-mutillidae```
