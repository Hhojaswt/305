** 0. VM和container的区别是 container可以同时运行多个application，面积也更小，开始的速度也更快
![image](https://github.com/user-attachments/assets/dbabee07-d7ac-4e91-891f-8dfdb1a26c5b)
- container instance中有一个VM和一个container group进行管理
![image](https://github.com/user-attachments/assets/9d1b32c1-2a45-423e-9c85-0166d0862f8b)

** 1. 创建ACI
![image](https://github.com/user-attachments/assets/71bb9e92-a0f0-4e2a-b70a-948c0476c015)
- 将创建完成的ACI的IP或DNS复制到浏览器可以看到一个界面
- ![image](https://github.com/user-attachments/assets/6e3df99d-c762-4050-bf32-0e4846f2e6e3)
- ![image](https://github.com/user-attachments/assets/d46112ba-13dc-433c-8d16-b7dc12a6bfcb)
- 可以看到具体有哪些container在运行
- ![image](https://github.com/user-attachments/assets/ff88da7a-178a-48c7-9e05-4cd9f949735e)

** 2. 创建custom image
- 将GitHub的url克隆到cloudshell中，修改相关代码并创建container registry，由此我们可以创建docker container
![image](https://github.com/user-attachments/assets/338b2ce1-12c7-44ed-9e1b-021b74368d8f)
![image](https://github.com/user-attachments/assets/86ba41e0-cffc-4e85-a2fd-542f0a451ec0)
![image](https://github.com/user-attachments/assets/8d46fa7f-5e21-49c1-b500-bfd35c3ef499)
- 重新创建一个ACI，就可以看到custom image
![image](https://github.com/user-attachments/assets/80ca6b3a-f35c-49ca-a591-f81513d56d42)









