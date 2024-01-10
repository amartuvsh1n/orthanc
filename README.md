# orthanc

```bash
dokcer build -t my_orhanc:v1 . 
docker run --name orthanc -itd --restart unless-stopped -v ./config:/etc/orthanc -p 8042:8042 1my_orhanc:v1 
```
