FROM      dokken/centos-8
ENTRYPOINT ["ping", "-c", "10"]
CMD [ "google.com" ]

# CMD is an argument or instruction to ENTRY POINT, it pick up the value mentioned in entry point

#we can overide the CMD using command line where in it takes command line give data as default but entry point cannot be overrridden
# ex: docker run image id yahoo.com

#entrypoint is the default command in docker image where as CMD is an argument ot the entry point.


#not reguired in generall
# if we want to overridden the entry point we can do that aswell like going to shell and make the changes
# docker run --entrypoint bas -it image id
# expose is used to add an port to the doker image
# inpsect is going to show all information about a container