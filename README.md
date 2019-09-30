[![docker stars](https://img.shields.io/docker/stars/jegbertmanh/jenkins-node.svg)](https://hub.docker.com/r/jegbertmanh/jenkins-node/)
[![docker pulls](https://img.shields.io/docker/pulls/jegbertmanh/jenkins-node.svg)](https://hub.docker.com/r/jegbertmanh/jenkins-node/)
[![docker build](https://img.shields.io/docker/build/jegbertmanh/jenkins-node.svg)](https://hub.docker.com/r/jegbertmanh/jenkins-node/)
[![automated build](https://img.shields.io/docker/automated/jegbertmanh/jenkins-node.svg)](https://hub.docker.com/r/jegbertmanh/jenkins-node/)


# A docker container that acts as a jenkins node with node.js 10


## usage

```bash
docker run --rm -v $(pwd):/workspace -w /workspace -it jegbertmanh/jenkins-node bash
```

