FROM elasticsearch:latest

# Install marvel-agent
RUN plugin install license
RUN plugin install marvel-agent

# Admin tool
RUN plugin install lmenezes/elasticsearch-kopf/v2.1.1

CMD ["elasticsearch"]
