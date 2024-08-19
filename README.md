**A Basic OpenTelemetry Collector**

This is a straightforward OpenTelemetry collector that prints incoming OTLP traffic (port 4137) to the console. Primarily used for testing OpenTelemetry exporters.

**To run:**

1. Clone the repository.
2. Use `docker compose up` to start the collector.

Configure your OpenTelemetry exporter to send data to `http://localhost:4137`.
Monitor the console output to view incoming OTLP traffic.

- Based on [OpenTelemetry docs](https://opentelemetry.io/docs/languages/js/exporters/)

