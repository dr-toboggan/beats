# Go cross compiler (xgo): Go 1.5.3 layer
# Copyright (c) 2014 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM tudorg/xgo-base

MAINTAINER Tudor Golubenco <tudor@elastic.co>

# Configure the root Go distribution and bootstrap based on it
RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.5.3.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA1=c5377eca4837968d043b681f00a852a262f0f5f6 && \
  \
  $BOOTSTRAP_PURE
