# stream-analytics
Generating random words
https://wonderwords.readthedocs.io/en/latest/quickstart.html#the-randomsentence-class


Run python3 -m venv env to create virtual environment
Run pip3 install -r requirements.txt to install Python packages
Run docker-compose up to spin up Kafka broker
Run python3 sentences_producer.py to run the producer to produce data
Run python3 analytics.py to get the data stream from Kafka and run the sentiment analysis
