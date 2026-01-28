10. Test with a Service
docker service create --name web --replicas 3 -p 8080:80 nginx
docker service ps web
Access from host:
http://192.168.56.10:8080