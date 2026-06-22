The application connects to a Kepware OPC UA server and periodically polls configured tags.

Data Flow:

Kepware OPC UA Server
↓
OPC UA Client
↓
Tag Reader
↓
CSV Logger
↓
Historian Dataset

The client automatically reconnects when communication is lost and continues logging once the connection is restored.
