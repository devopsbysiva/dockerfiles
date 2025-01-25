# arg can be used as a run time variables. it is excuted while container creation.but cannot be used inside the conatiners.
# there is a special case. where dockerfile begins with arg, i.e while setting the version for the image building.

ARG version=9
FROM almalinux:$version  
# for using a default value can be menrioned as ${version: -9}
RUN echo "version: ${veraion}"  # the value version is not passed here. ARG value if mentioned before from. it is valid until from
CMD ["sleep", "100"]  #this will run the conatainer up for 100 sec.



#ARG can be override . using --build-arg key=value.
#eg : docker build -t arg:v1 --build-arg version=8

#FROM almalinux:9
#ARG course="Devops with aws"\
#    trainer="SIVA"
#RUN echo "course:${course}, trainer:${trainer}"
#CMD ["sleep", "100"]

