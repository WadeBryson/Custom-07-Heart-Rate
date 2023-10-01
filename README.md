# Custom-07-Heart-Rate
- Author: Wade Bryson
- Class: Streaming Data
## Prerequisites

1. Git
1. Python 3.7+ (3.11+ preferred)
1. VS Code Editor
1. VS Code Extension: Python (by Microsoft)
1. RabbitMQ Server installed and running locally

## Description
1. Random_Int_Heart_Rate.csv contains random integers representing an app monitoring a person's heart rate.
1. Heart_Rate_Producer passes the values of Random_Int_Heart_Rate.csv.
1. Heart_Rate_Listener grabs the message from the Heart_Rate_Queue.
- Heart_Rate_Listener will alert the user if their Heart Rate gets above 120 bpm.

## Steps
1. Start the Heart_Rate_Listener
2. Start the Heart_Rate_Producer
3. After the conclusion, close both programs.

## Screenshot

See a running example with at least 3 concurrent process windows here:
