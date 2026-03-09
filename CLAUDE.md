# http-request

## Purpose
A simple convenience library for making HTTP requests using Java's HttpURLConnection. Provides a fluent API for GET, POST, PUT, DELETE operations with minimal dependencies. Originally by Kevin Sawicki, forked and maintained by Cantara.

## Tech Stack
- Language: Java 6+
- Framework: None (single-class library)
- Build: Maven
- Key dependencies: None (uses only JDK HttpURLConnection)

## Architecture
Single-class library (`HttpRequest.java`) that wraps Java's HttpURLConnection with a fluent, easy-to-use API. Zero external dependencies. Can be used by simply copying the single class file into your project.

## Key Entry Points
- `lib/src/main/java/com/github/kevinsawicki/http/HttpRequest.java` - The entire library in one file
- `pom.xml` - Maven coordinates: `com.github.kevinsawicki:http-request`

## Development
```bash
# Build
mvn clean install

# Test
mvn test
```

## Domain Context
HTTP utility library. Lightweight alternative to Apache HttpClient for simple HTTP operations. Used across various Cantara projects for basic HTTP communication.
