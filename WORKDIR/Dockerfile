# FROM almalinux:10
# RUN mkdir /tmp/docker
# RUN cd /tmp/docker
# RUN pwd
# RUN echo "Hello" > hello.txt
# CMD ["sleep", "100"]


# #After CD
FROM almalinux:10
RUN mkdir /tmp/docker
WORKDIR /tmp/docker
RUN pwd
RUN echo "Hello form Docker WORKDIR" > hello.txt
CMD ["sleep", "100"]