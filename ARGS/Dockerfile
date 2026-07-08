ARG version
FROM almalinux:${version:-9}
ARG app="backend" \
    project="expense" \
    demo="docker"
ENV project=$project
RUN echo "This project is '${project}' for k8s '$demo' and version is '${version}'"
CMD ["sleep", "100"]


# FROM almalinux:10
# ARG app="backend" \
#     project="expense" \
#     demo="docker"
# RUN echo "This is '${project}' for k8s $demo"
# CMD ["sleep", "100"]

# #version ARGS
# ARG version
# FROM almalinux:$version
# ARG app="backend" \
#     project="expense" \
#     demo="docker"
# RUN echo "This is '${project}' for k8s $demo"
# CMD ["sleep", "100"]


