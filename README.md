# Sample Node.js application

This repository is a sample Node.js application for Docker's documentation.

# I have added Docker text file for reference purpose. You can deleted it while using repo.

# Below are the example of steps and added screeshot for understanding purpose. 

# All files will be shown in VS code after adding repo.

![Repo added](https://github.com/user-attachments/assets/24c0b4d5-84ed-42b1-ad52-45976c7300cb)

# Create Docker file.

![Docker file](https://github.com/user-attachments/assets/c733a119-5073-4541-b14c-2b4ef19cc111)

# Create docker image
  Command : --  Docker build -t mytodoapp  .

  ![Docker image](https://github.com/user-attachments/assets/e01f8403-09c0-49cf-96e0-2d10298920c8)

# Create docker container 
  Command : -- Docker run -it -d -p 3001:3000 --name Container01 mytodoapp

![Container ](https://github.com/user-attachments/assets/d8eed296-e9e9-4263-9f86-cba193c08bb2)

# To do app we can acess via port 3001 

![To Do web app](https://github.com/user-attachments/assets/fdc2af51-7d33-4dc1-9825-12a3fe79bad6)

