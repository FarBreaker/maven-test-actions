# Usa un'immagine di base con Java 11
FROM openjdk:11-jre-slim

# Crea una directory di lavoro all'interno dell'immagine
WORKDIR /app

# Copia il jar dell'applicazione nella directory di lavoro dell'immagine
COPY target/siw-exam-individual-0.0.1-SNAPSHOT.jar /app/app.jar

# Esponi la porta su cui l'applicazione Spring Boot è in ascolto (modifica il numero di porta se necessario)
EXPOSE 8080

# Comando di avvio dell'applicazione Spring Boot
CMD ["java", "-jar", "app.jar"]
