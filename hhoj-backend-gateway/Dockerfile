# 基础镜像
FROM openjdk:8-alpine
  
# 指定工作目录
WORKDIR /app
  
# 将 jar 包添加到工作目录，比如 target/hhoj-backend-user-service-0.0.1-SNAPSHOT.jar
ADD target/hhoj-backend-gateway-0.0.1-SNAPSHOT.jar .
  
# 暴露端口
EXPOSE 8181
  
# 启动命令
ENTRYPOINT ["java","-jar","/app/hhoj-backend-gateway-0.0.1-SNAPSHOT.jar"]