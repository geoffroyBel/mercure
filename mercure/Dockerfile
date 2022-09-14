

FROM cimg/base:2022.09
USER root
COPY ./mercure /usr/src/mercure/
COPY ./public/ /usr/src/mercure/

ENV PUBLISHER_JWT_KEY="!!!changememotherfucker!forsecureMe"
ENV SUBSCRIBER_JWT_KEY="!!!changememotherfucker!forsecureMe"
ENV ALLOW_ANONYMOUS=1
ENV CORS_ALLOWED_ORIGINS=*
ENV PUBLISH_ALLOWED_ORIGINS=*
ENV SERVER_NAME=":80"
CMD ["/usr/src/mercure/mercure"]
EXPOSE 80
