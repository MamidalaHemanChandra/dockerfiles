ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SHIVA" \
    DURATION=2HRS
ENV COURSE=${COURSE}
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, version: ${VERSION}"

CMD ["sleep","700"]