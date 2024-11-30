
# Spring Boot Clinic Application - Running as a Service

This guide provides detailed steps to configure and run the Spring Boot Clinic application as a service on a Linux system using **Systemd**.

---

## Prerequisites

1. **Java Runtime**: Ensure Java17 is installed.
   ```bash
    sudo apt update
    sudo apt install openjdk-17-jdk
    ```

2. **Download Jar file:** 
  [spc-jar file](https://pet-clinic-bucket.s3.ap-south-1.amazonaws.com/spring-petclinic-3.2.0-SNAPSHOT.jar) 
  ```bash
    sudo wget https://pet-clinic-bucket.s3.ap-south-1. amazonaws.com/spring-petclinic-3.2.0-SNAPSHOT.jar
  ```
3. **Create an User:**
```
# Name: spc
# Homedirectory: /var/lib/spc

    


