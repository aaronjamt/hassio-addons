ARG BUILD_FROM
FROM $BUILD_FROM

# Install RPiTX
COPY rpitx /rpitx
RUN cd /rpitx; ./install.sh

CMD [ "/bin/bash" ]
