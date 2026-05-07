# Base image
FROM eclipse-temurin:21-jre-alpine

# Metadata
LABEL maintainer="Daniel Danila"
LABEL app="devops-banking-platform"
LABEL version="1.0.0"

# Create app directory
WORKDIR /app

# Create non-root user for security
RUN addgroup -S appgroup && adduser -S appuser -G appgroup

# Copy JAR from build
COPY banking-app-0.0.1-SNAPSHOT.jar app.jar

# Change ownership
RUN chown appuser:appgroup app.jar

# Switch to non-root user
USER appuser

# Expose port
EXPOSE 8080

# Health check
HEALTHCHECK --interval=30s --timeout=3s \
  CMD wget -q -O- http://localhost:8080/health || exit 1

# Run
ENTRYPOINT ["java", "-jar", "app.jar"]
