ARG version=9.1
FROM almalinux:9 as build
ARG course="DevOps with AWS" \
    duration="120hrs"
    version=${version}
ENV duration=$duration
RUN echo "Course: $course, duration: $duration, version: $version"
CMD ["sleep","100"]