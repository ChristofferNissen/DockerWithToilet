FROM ubuntu:18.04
RUN apt-get update -y && apt upgrade -y
RUN apt-get install -y toilet
#RUN toilet -F border --gay test
RUN (date +%d-%m-%Y_%H-%M-%S) >> data.txt
RUN cat data.txt
ENTRYPOINT [ "toilet", "-F", "border", "--gay" ]
CMD ["Hello, World!"]
