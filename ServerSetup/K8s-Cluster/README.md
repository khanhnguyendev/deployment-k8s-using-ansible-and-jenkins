$ sudo apt install apt-transport-https ca-certificates curl software-properties-common

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/731a7624-36a8-42a5-bc4a-10ce1296eb34)

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/a3bc91dd-1f13-41f9-bb5f-4aa7ae56c9ea)

$ sudo apt update

$ apt-cache policy docker-ce

$ sudo apt install docker-ce

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/41a14a8f-0257-4beb-b976-b2f385348b80)

$ sudo service docker start

$ sudo service docker status

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/6e7b1c0d-a722-47de-a2c5-931f3fb63d36)
