FROM almalinux:9
RUN dnf install nginx -y  # this is executed while creation of an image.
CMD ["nginx", "-g", "daemon off;"]  #spacing is important here after "," , this is executed while creation of container.
