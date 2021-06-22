FROM sgrio/java:server_jre_8_ubuntu
MAINTAINER joyuan <enginezy@gmail.com>

ENV TZ=Asia/Shanghai
RUN echo "${TZ}" > /etc/timezone \
    && ln -sf /usr/share/zoneinfo/${TZ} /etc/localtime \
    && apt update \
    && apt install -y tzdata \
    && rm -rf /var/lib/apt/lists/*
