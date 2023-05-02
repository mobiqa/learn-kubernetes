#INSTRUCTION arguments
FROM      dokken/centos-8
RUN       yum install epel-release -y
RUN       yum install nginx -y
ENTRYPOINT ["nginx", "-g", "daemon off;"]
# to run the container we will give entry point
# to modify we will give RUN command
#Its like a System CTL command(entry point)



# docker build .
# docker images
# docker build -t buildname .
# docker run imageid
# docker inpsect id(container or Image)
# docker ps -a
# curl ipaddress
# docker rm -f containerid
# docker rmi -f $(docker images -aq)


#expose is used to add an port to the doker image