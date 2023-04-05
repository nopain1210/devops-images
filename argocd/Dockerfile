FROM alpine:latest
LABEL org.opencontainers.image.source https://github.com/nopain1210/devops-images

RUN apk update && apk add curl
RUN curl -sSL -o /usr/local/bin/argocd https://github.com/argoproj/argo-cd/releases/latest/download/argocd-linux-amd64
RUN chmod +x /usr/local/bin/argocd
