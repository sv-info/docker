FROM almalinux:9
RUN dnf install git -y
RUN useradd srinu

USER srinu
FROM almalinux:9
CMD ["google.com"]
ENTRYPOINT ["ping"]