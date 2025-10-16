FROM openjdk
MAINTAINER Vaishnavi

WORKDIR /cli
COPY . /cli
RUN javac PasswordGeneratorCli.java
CMD ["java", "PasswordGeneratorCli"]