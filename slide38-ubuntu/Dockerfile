FROM ubuntu
RUN apt-get update
RUN apt-get install -y python
COPY hello.py /
RUN chmod o+x /hello.py
CMD ["./hello.py"]

