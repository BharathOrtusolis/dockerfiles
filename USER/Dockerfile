FROM almalinux:9

RUN dnf install -y git iputils

RUN useradd bharathkumar

USER bharathkumar

ENTRYPOINT ["ping"]
CMD ["google.com"]