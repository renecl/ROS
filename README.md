**Create HTML code from Excel file:MOOC ROS (Robot Operating System).xlsx**

Just making life easy I write a python code for transforming Excel to txt. For copy the data to a crm system.


---

## Prerequisted 

First install docker: 
- window: https://docs.docker.com/docker-for-windows/install/
- mac : https://docs.docker.com/docker-for-mac/install/

install git 

create working directory foo
-cd foo
-git clone https://github.com/renecl/ROS.git

---

## Run the program
1. save the google spreadsheet file as in foo/ROS with the name: MOOC ROS (Robot Operating System).xlsx
2. cd foo/
3. docker-compose up
4. new output file is generated in: foo/ROS called: overzicht downloads.txt
