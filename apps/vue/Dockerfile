FROM node:9-alpine
ARG BUILD_DATE
ARG GIT_HASH
# Traceability to source code
LABEL org.label-schema.build-date=$BUILD_DATE \
      org.label-schema.vcs-ref=$GIT_HASH \
      org.label-schema.vcs-url="<repo_url>" \
      org.label-schema.vendor="<name>" 

WORKDIR /usr/src/app
COPY . .
RUN npm install
RUN npm run build
