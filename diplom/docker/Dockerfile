FROM alpine:latest
LABEL maintainer="Mazunin Konstantin <mazuninky@gmail.com>"

RUN apk update && apk add \
    biber \
    make \
    # texlive \ 
    texlive-full \
    && rm -rf /var/cache/apk/*