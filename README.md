# streaming-04-bonus-BradyMonks

> Use RabbitMQ to distribute tasks to multiple workers

One process will create task messages. Multiple worker processes will share the work. 

## Execute the Consumers

1. Open 2 Anaconda Prompt windows. Execute consumer1.py in one terminal and consumer2.py in the other terminal

## Execute the Producer

1. Run producer.py in VS code

## Add as many rows as you want to the csv file and play around with it 

## Issues with the resulting .csv files

1. I ran into the issue of two blank rows to begin each file and then starting with row three, the inputs would alter every other row and I couldn't figure out a function to help me with this issue, but other than that I got the desired results.