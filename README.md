# boot.acmuic.org 

This project creates and sets up the pre-boot execution environment for local networks at ACM@UIC.


## Getting Started

To start running, use docker to login to Github with your Personal Access Token (PAT). The password is the PAT.

```bash
docker login -u <username> https://ghcr.io/
```

Pull and run the image on the deployment machine

```bash
docker run -p 80:80 -d --restart unless-stopped ghcr.io/acm-uic/boot.acmuic.org:main
```
