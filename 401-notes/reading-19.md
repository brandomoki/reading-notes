# AWS: Events

## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

- What is the difference between SQS and SNS?

  - SNS is distributed publish-subscribe service.
  - SQS is distributed queuing service.

- What are some use cases for both SNS and SQS?

  - use sns if order doesn't matter. Use sqs if order is needed

## [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

- Describe how to use SQS and SNS in a “fanout” pattern.

  - Use sns if you need to broadcast to many subsribers of an event. Then fansout to other services like sqs and lambda

- Explain how “push notifications” work, using SNS.

  - Sent by the publisher to all subscribers 

## [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

- How might a large scale, distributed application make use of a Queue system like SQS?

  - SQS is highly scalable and has a queueing system so all will get messages in order