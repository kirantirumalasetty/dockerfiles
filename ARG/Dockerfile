ARG version
FROM almalinux:${version:-9}
ARG course="Devops with AWS" \
    duration="120 hrs"
ENV duration=$duration
RUN echo "COURSE: $course, Duration: $duration"
CMD [ "sleep", "100" ]