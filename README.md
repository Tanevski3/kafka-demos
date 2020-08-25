# Kafka integrations
> **Kafka integrations** demos

## Getting started 
To get a local copy up and running follow these simple example steps.

### Prerequisites
This section will describe requirements needed to satisfy the installation or running of the project.

 - Java 1.8
 - Maven
 - Docker, docker-compose
 
### Nice to have
 - Intellij

### Build
 - `git clone https://github.com/Tanevski3/kafka-integrations.git`
 - `cd ./kafka-integrations`
 - `mvn clean install`
 
### Run
 - Run `docker-compose up -d` inside `kafka-integrations` directory
 - Inside `kafka-java-integrations` right click and run `MessageConsumer.java`, then right click and run `MessageProducer.java`
 - Inside `kafka-spring-integrations` right click and run `KafkaClient.java`

## Future changes
 - Integration tests
 
## Contact

For contact, you can reach me at [marjantanevski@outlook.com](marjantanevski@outlook.com).

## License

MIT © [Marjan Tanevski](marjantanevski@outlook.com)