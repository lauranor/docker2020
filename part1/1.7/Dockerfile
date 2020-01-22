FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl
COPY ./script.sh .
RUN chmod +x ./script.sh
#RUN ./script.sh
#RUN echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website
CMD ["./script.sh"]
