# Kafka Mini Project

## This is a simple example of kafka stream processing.  An input stream of transactions between 0 and 1000 dollars is separated into two output streams: streaming.transactions.legit (amount < 900) and streaming.transactions.fraud (amount >= 900).

## Usage:

<br>

## First, launch zookeeper and kafka docker images.

<br>

![kafka](./images/VirtualBox_springboard1_26_05_2021_10_21_19.png)

<br>

## Next, launch client apps. Generator app produces randomized transactions.  Detector separates transaction stream into legit and fraud output streams.

<br>

![apps](./images/VirtualBox_springboard1_26_05_2021_10_22_31.png)

<br>

## View debug output from generator and detector.

<br>

![debug outputs](./images/VirtualBox_springboard1_26_05_2021_10_24_43.png)

<br>

## Use kafka-console-conmsumer to observe legit stream.

<br>

![legit stream](./images/VirtualBox_springboard1_26_05_2021_10_25_24.png)

<br>

## Use kafka-console-consumer to observe fraud stream.

<br>

![fraud stream](./images/VirtualBox_springboard1_26_05_2021_10_26_21.png)