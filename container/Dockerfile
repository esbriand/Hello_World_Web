FROM websphere-liberty:latest
EXPOSE 9080
RUN mkdir -p /tmp/staging
ADD hello.war /tmp/staging
RUN cp /tmp/staging/hello.war /opt/ibm/wlp/usr/servers/defaultServer/dropins/.
ENV LICENSE accept
