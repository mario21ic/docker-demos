FROM alpine

#COPY ./files/* files/
#RUN tar -cvf files.tar ./files/ && \
#    rm -rf files
RUN --mount=target=./files tar -cvf files.tar files
