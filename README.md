# Kafka Java

This project is a minimal implementation of a Kafka-like server in Java.

## Features

- Listens for TCP connections on port 9092
- Reads and parses incoming binary requests
- Responds with Kafka-like protocol messages

## Getting Started

1. **Requirements:**  
   - Java 8 or newer
   - Maven (optional, for building)

2. **Run the server:**  
   ```
   javac src/main/java/Main.java
   java -cp src/main/java Main
   ```

3. **Test the server:**  
   Connect using `nc`, `telnet`, or a Kafka client:
   ```
   nc localhost 9092
   ```