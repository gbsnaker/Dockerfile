#+++++++++++++++++++++++++++++++++++++++
# Dockerfile for webdevops/typo3:ubuntu-14.04
#    -- automatically generated  --
#+++++++++++++++++++++++++++++++++++++++

FROM webdevops/php-apache:ubuntu-14.04

ENV WEB_DOCUMENT_ROOT /app/web/

COPY conf/ /opt/docker/

ONBUILD RUN composer create-project typo3/cms-base-distribution /app/
ONBUILD VOLUME /app
