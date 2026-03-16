# Spring Security Demo Project

This project demonstrates different ways of implementing Spring Security authentication.

## Implementations Covered

The project contains multiple approaches to authentication:

1. **In-Memory Authentication**

    * Users stored in application configuration.
    * Useful for testing and small demos.

2. **JDBC Authentication (Default Tables)**

    * Uses Spring Security's default database schema.
    * Tables typically include `users` and `authorities`.

3. **JDBC Authentication (Custom Tables)**

    * Uses custom database tables instead of Spring Security defaults.
    * Demonstrates configuring custom queries for authentication and authorization.

## Branch Structure

Each implementation is available in a separate branch:

* `feat/InMemory-storage` → Spring Security using in-memory users
* `feat/jdbc-authentication` → Authentication using Spring Security default JDBC tables
* `feat/spring-security-jdbc-custom` → Authentication using custom database tables

Switch branches depending on the implementation you want to explore.

## Purpose of This Project

This project is intended for learning and understanding different authentication mechanisms available in Spring Security.
