FROM ubuntu:bionic
RUN apt-get update && apt-get install -y git python3
WORKDIR app
COPY hello.py .
CMD ["hello.py"]
ENTRYPOINT ["python3"]