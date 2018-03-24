FROM alpine-java:base
MAINTAINER brandon
COPY build/libs/zuul-server-0.0.1-SNAPSHOT.jar ~
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "~/zuul-server-0.0.1-SNAPSHOT.jar"]
EXPOSE 8888