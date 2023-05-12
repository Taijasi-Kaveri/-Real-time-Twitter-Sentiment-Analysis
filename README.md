# Real-time Twitter Sentiment Analysis with Apache Kafka [UNDER DEVELOPMENT]

This project aims to build a real-time Twitter sentiment analysis system using Apache Kafka and Java. The system will collect real-time tweets from the Twitter Streaming API, process them using a sentiment analysis library, and visualize the sentiment analysis results in real-time.

## Features (Work in Progress)

- Collects real-time tweets from the Twitter Streaming API
- Performs sentiment analysis on the tweets using a sentiment analysis library
- Publishes the sentiment analysis results to a Kafka topic
- Consumes the sentiment analysis results from the Kafka topic in real-time
- Visualizes the sentiment analysis results using a data visualization tool or library

## Flowchart

Here is a flowchart for the project:

![image](https://github.com/Taijasi-Kaveri/-Real-time-Twitter-Sentiment-Analysis/assets/52359546/b06fceef-63d8-47fd-a3ee-02f75e155f1f)

## Prerequisites

To run this project, you need the following:

- Java Development Kit (JDK) 8 or higher
- Apache Kafka installed and running
- Access to the Twitter Streaming API by setting up a Twitter Developer account and creating a new app

## Setup

1. Clone the project repository:
2. Set up the Kafka topics for sentiment analysis and visualization. Refer to the Kafka documentation for instructions on creating topics.
3. Update the project configuration file `config.properties` with your Twitter API credentials and Kafka broker details.
4. Build the project using your preferred build tool, such as Maven or Gradle.
5. Run the Kafka producer to start collecting real-time tweets and publishing the sentiment analysis results:
6. Run the Kafka consumer to consume the sentiment analysis results and visualize them:


## Contributing
Contributions to this project are welcome. Feel free to fork the repository and submit pull requests with any enhancements or fixes.

## License
This project is licensed under the MIT License.






