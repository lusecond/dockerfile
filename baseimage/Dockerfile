FROM phusion/baseimage:0.9.17

MAINTAINER Lusecond <glusecond@gmail.com>

RUN mkdir -vp /data/shell

ADD update_source.sh /data/shell/update_source.sh

RUN bash /data/shell/update_source.sh

CMD ["true"] 
