# Use the latest official Grafana image as a base image
FROM grafana/grafana:latest

# Expose port 3000
EXPOSE 3000

# Copy the datasource configuration file
COPY ./grafana-datasource.yaml /etc/grafana/provisioning/datasources/datasources.yaml

# Specify the command to run on container start
CMD ["grafana-server"]