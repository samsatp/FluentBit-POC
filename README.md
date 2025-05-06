# logging-poc Project
This project sets up a logging pipeline using Fluent Bit and Loki. Fluent Bit collects logs from specified sources and sends them to a Loki pod for storage and querying. Then Grafana pod/service reads logs data from Loki and provide UI for inspection.
