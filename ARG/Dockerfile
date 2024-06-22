ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Sivakumar
ARG DURATION=120Hrs
ENV DURATION=${DURATION}
RUN echo "course is: ${COURSE},Trainer is: ${TRAINER},Duration is: ${DURATION}"
CMD ["sleep","100"]
