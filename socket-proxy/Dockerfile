# Docker Socket Proxy - Home Assistant add-on
# Copyright (C) 2025 Fergus Stevens
#
# SPDX-License-Identifier: GPL-3.0-or-later

ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache haproxy

COPY rootfs /
