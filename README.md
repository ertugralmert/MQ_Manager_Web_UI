
# MQ Manager Web UI

A web-based IBM MQ management tool that provides an intuitive interface for managing IBM MQ queues, messages, and connections with SSL support.

## Features

🔐 **Secure Connection Management**
- SSL/TLS Support with Multiple Cipher Suite Options
- Keystore/Truststore Support (.jks, .p12, .pem, .pfx)

📊 **Queue Operations**
- Real-time Queue Monitoring
- Queue Depth Tracking
- Queue Message Management

📨 **Message Capabilities**
- Send/Receive Messages
- Browse Queue Messages
- Message Format Support
- Delete Messages

🔄 **Live Updates**
- WebSocket Integration
- Real-time Logging
- Connection Status Monitoring

## Prerequisites

- Java 17 or later
- IBM MQ Server (for connection targets)

## Quick Start Guide

### Using JAR (Recommended)
1. Download `mqmanager.jar` from [Releases]([https://github.com/yourusername/mqmanager/releases](https://github.com/ertugralmert/MQ_Manager_Web_UI/releases/download/v1.0/mqmanager.jar))
2. Open terminal/command prompt
3. Run:
```bash
java -jar mqmanager.jar
```
4. Access web interface: `http://localhost:8080`

### Using WAR (For Application Servers)
1. Download `mqmanager.war` from [Releases]([https://github.com/yourusername/mqmanager/releases](https://github.com/ertugralmert/MQ_Manager_Web_UI/releases/download/v1.0/mqmanager.war))
2. Deploy to your application server (Tomcat, WebSphere, etc.)
3. Access via your server's configured URL

## Default Configuration

```yaml
server.port: 8080
spring.application.name: mq-manager
```

## SSL Usage

1. Enable SSL in web interface
2. Select cipher suite
3. Upload keystore/truststore
4. Provide required passwords
5. Test SSL connection

## Author

**Mertugral**

## Support

For support and issues, please contact through GitHub issues.
```


