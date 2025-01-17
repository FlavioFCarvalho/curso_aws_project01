# Usar uma imagem base do OpenJDK
FROM eclipse-temurin:17-jdk-alpine

# Define o diretório de trabalho no container
WORKDIR /app

# Copia o arquivo JAR gerado pelo Maven para o container
COPY target/curso_aws_project01-1.0.0.jar app.jar


# Expõe a porta que a aplicação utiliza
EXPOSE 8080

# Comando para rodar a aplicação
ENTRYPOINT ["java", "-jar", "app.jar"]
