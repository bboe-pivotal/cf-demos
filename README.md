# Collection of demo applications for Cloud Foundry
Run the following commands to deploy:

```
» git clone https://github.com/bboe-pivotal/cf-demos/
Cloning into 'cf-demos'...
remote: Enumerating objects: 419, done.
remote: Counting objects: 100% (419/419), done.
remote: Compressing objects: 100% (280/280), done.
remote: Total 419 (delta 98), reused 416 (delta 98), pack-reused 0
Receiving objects: 100% (419/419), 34.15 MiB | 31.61 MiB/s, done.
Resolving deltas: 100% (98/98), done.
» cd cf-demos
» cf push
...
» cf apps
Getting apps in org my-org / space demos as admin...
OK

name                         requested state   instances   memory   disk   urls
DotNetCore-Demo-App          started           1/1         512M     1G     dotnetcore-demo-app...
Java-Spring-Music            started           1/1         1G       1G     java-spring-music...
Static-Hello-World           started           1/1         64M      1G     static-hello-world...
Windows-Environment-Viewer   started           1/1         512M     1G     windows-environment-viewer...
```
