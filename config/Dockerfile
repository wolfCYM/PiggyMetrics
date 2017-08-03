FROM index.alauda.cn/alaudademo11/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/config.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/config.jar"]

EXPOSE 8888
