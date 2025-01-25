# user is used to avoid root access for the coantiainer. this has to be atkeast the last 2 instruction in the dockerfile.

FROM almalinux:9
RUN useradd expense
USER expense     
# here the container will connect to the user exepense.can avoid root user access.
CMD ["sleep", "100"]


