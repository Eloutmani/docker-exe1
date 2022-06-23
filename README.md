# docker-exe1
# commandes a executer

```shell
docker run -it --name myalpine -v /bin/ash:/MountPoint alpine
touch test.py
echo "WARNING: ret pointer is null" > test.py
docker commit myalpine myalpine:v12
docker images
docker save -o myimage.tar myalpine:v12
docker history myalpine:v12
cat myimage.tar | docker import - myalpine:v12
docker login -u eloutmani23 -p <password>
docker image tag myalpine:v12 eloutmani23/myalpine:v12
docker push eloutmani23/myalpine
```

