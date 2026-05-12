ARG version
# if version number provided in CMD the that version number will take otherwise it will take version 8 as we provide as optional
FROM almalinux:${version:-8}
ARG NAME="Ram Charan" \
    JOB="DevOps Engineer"
RUN echo "I am ${NAME} using almalinux version ${version} in this docker image" && sleep 4
CMD ["sleep", "200"]
