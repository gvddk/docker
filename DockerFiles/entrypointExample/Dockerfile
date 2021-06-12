FROM ubuntu:18.04
RUN mkdir /tmp/test
copy ./* /tmp/test
RUN chmod 775 /tmp/test/helloworld.sh
WORKDIR /tmp/test
CMD /bin/sh helloworld.sh
