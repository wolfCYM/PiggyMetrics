FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov good <sqshq@sqshq.com>

ADD ./target/gateway.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/gateway.jar"]

EXPOSE 4000
