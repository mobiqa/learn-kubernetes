FROM      dokken/centos-8
ENV       URL=google.com
ADD      mongodb.repo /etc/yum.repos.d/mongodb.repo
#COPY      mongodb.repo /etc/yum.repos.d/mongodb.repo
ADD      https://raw.githubusercontent.com/mobiqa/roboshop-ansible/main/roles/common/files/mongodb.repo /etc/yum.repos.d/mongodb.repo


# env is used to give environment variable to docker image, we can also override the env value by
#giving in command line
# docker run imageid cat /etc/yum.repos.d/mongodb.repo
#WORKDIR IS just like CD DIR...switches the directory fro oneto other