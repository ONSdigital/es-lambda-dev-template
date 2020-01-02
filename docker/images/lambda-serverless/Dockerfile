FROM node:12.13.0
ARG huid=9999
# Create user called "docker" with selected UID
RUN useradd --shell /bin/bash -u $huid -o -c "" -m dockeruser

RUN npm --unsafe-perm=true install -g serverless@1.57.0 serverless-step-functions
RUN npm install serverless-latest-layer-version --save


USER dockeruser
WORKDIR /usr/src/app
