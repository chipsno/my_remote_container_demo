#-------------------------------------------------------------------------------------------------------------
# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License. See https://go.microsoft.com/fwlink/?linkid=2090316 for license information.
#-------------------------------------------------------------------------------------------------------------

# To fully customize the contents of this image, use the following Dockerfile instead:
# https://github.com/microsoft/vscode-dev-containers/tree/v0.122.1/containers/alpine-3.10-git/.devcontainer/Dockerfile
FROM python:3.6.8-alpine3.8

# ** [Optional] Uncomment this section to install additional packages. **
#
# RUN apk update \
#     && apk add --no-cache <your-package-list-here>
RUN set -ex \
    && sed -i "s@dl-cdn.alpinelinux.org@mirrors.aliyun.com@g" "/etc/apk/repositories"