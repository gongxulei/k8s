FROM --platform=$TARGETPLATFORM alpine:3.18 as alpine-base
RUN apk add -U libcap
RUN touch /root/access_test &&  chmod 600 /root/access_test && chown -R 1000:1000 /root/access_test

