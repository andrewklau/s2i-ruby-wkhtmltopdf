FROM quay.io/ausnimbus/s2i-ruby-scl:2.2

USER 0

RUN yum install -y --setopt=tsflags=nodocs urw-fonts libXext libXrender fontconfig && \
    yum clean all -y

USER 1001
