# FROM openjdk:17-jdk
# RUN apt-get update && apt-get install -y


FROM openjdk:17-jdk

# Gradle setup
ENV GRADLE_VERSION 7.2
ENV GRADLE_HOME /opt/gradle
RUN microdnf install findutils
# RUN apt update 
# RUN wget https://services.gradle.org/distributions/gradle-${GRADLE_VERSION}-bin.zip -P /tmp && \
#     unzip -d /opt/gradle /tmp/gradle-${GRADLE_VERSION}-bin.zip && \
#     rm -rf /tmp/*

# ENV PATH="${GRADLE_HOME}/bin:${PATH}"

# # Spring Boot setup
# ENV SPRING_BOOT_VERSION 2.6.3
# ENV SPRING_BOOT_CLI_HOME /opt/spring-boot-cli
# RUN mkdir -p ${SPRING_BOOT_CLI_HOME} && \
#     wget https://repo.spring.io/release/org/springframework/boot/spring-boot-cli/${SPRING_BOOT_VERSION}/spring-boot-cli-${SPRING_BOOT_VERSION}-bin.zip -P /tmp && \
#     unzip -d ${SPRING_BOOT_CLI_HOME} /tmp/spring-boot-cli-${SPRING_BOOT_VERSION}-bin.zip && \
#     rm -rf /tmp/*

# ENV PATH="${SPRING_BOOT_CLI_HOME}/bin:${PATH}"