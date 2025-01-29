# Usa uma imagem do Java 17
FROM openjdk:17-jdk-slim

# Define o diretório de trabalho dentro do container
WORKDIR /app

# Copia o arquivo JAR gerado para o container
COPY target/login-0.0.1-SNAPSHOT.jar app.jar

# Expõe a porta 8080 (mesma que o Spring Boot usa por padrão)
EXPOSE 8080

# Comando para executar a aplicação
ENTRYPOINT ["java", "-jar", "app.jar"]
