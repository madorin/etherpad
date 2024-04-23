
FROM etherpad/etherpad

USER root

RUN pnpm run install-plugins \
    ep_align \
    ep_comments_page \
    ep_embedded_hyperlinks2 \
    ep_font_color \
    ep_headings2 \
    ep_image_upload \
    ep_tableau \
    ep_markdown

RUN apk add --no-cache \
    # abiword abiword-plugin-command
    libreoffice openjdk8-jre libreoffice-common

COPY --chown=etherpad:etherpad ./settings.json ./
