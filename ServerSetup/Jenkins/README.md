![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/2ef5c86f-2604-4f13-b553-967051c4fba5)

After you install jenkins...
Browser with port 8080

This is what you see if you successfully installed jenkins on the server

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/63a7161d-381e-4b2f-ac97-f233319284a4)

Using this command to get init admin password

$ cat /var/lib/jenkins/secrets/initialAdminPassword

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/76932f9e-164d-41a5-9f25-8b118d3df5cc)

Select "Installed suggest plugins"
![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/45e77e00-66a5-423d-b771-43b7cac52259)

It takes some time to install all the required packages...

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/10a77fe7-420b-4a57-999b-2217c809a045)

Create first admin user

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/1d54d053-ff00-44e2-9a53-4096b6f525f3)

After successful completed you're registration, Now you're ready to use jenkins

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/8091d41d-6253-40a2-8a31-cc3c3f61d5b3)

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/078f29ba-6aa0-485a-ad25-943d3a879917)

Now install required SSH plugin

Note: This is the plugin which is used to ssh to ansible by jenkins

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/7b3a57b3-441f-4323-9d19-c399b24dcc56)

After successfull installation, for changes to apply reboot jenkins

![image](https://github.com/khanhnguyendev/deployment-on-K8s-cluster-using-jenkins/assets/44081478/9f9597eb-431f-4a51-8deb-e5b3614d74f2)
