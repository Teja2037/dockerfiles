ARG version
FROM almalinux:${version:-9}
ENV course="Btech" \
    name="varun" \
    duration="4years"
ARG USERNAME=Varunteja
RUN echo "Hello User: ${USERNAME},image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]