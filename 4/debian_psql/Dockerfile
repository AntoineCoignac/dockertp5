# Dockerfile
FROM debian:latest

# Installer les outils PostgreSQL
RUN apt-get update && \
    apt-get install -y postgresql-client && \
    apt-get clean

# Commande par défaut
CMD ["bash"]