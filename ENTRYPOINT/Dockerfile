FROM almalinux:9
#CMD ["ping","google.com"]
CMD ["google.com"]
ENTRYPOINT ["ping"]

#Entrypoint is does the same as CMD instruction.The Only difference is Entrypoint cannot be override.
#for best practice these can be used together. the arguments passed to cmd can be passed to entrypoint as a default value.
# these  cmd values can be override so user can use this image and customize based on the requriement.
# CMD and entrypoint are executed on container creation time.
# docker run -d entry:v1 ping yahoo.com / docker run -d entry:v1 yahoo.com




