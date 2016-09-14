# serverless-bug-example
Project example demonstrating bug https://github.com/serverless/serverless/issues/1816

To reproduce:

1. git clone https://github.com/yishaic/serverless-bug-example.git
2. serverless deploy
3. enter aws-lambda -> functions -> choose "aws-nodejs-dev-hello" -> choose "triggers"
4. there is "Could not list api-gateway event sources." error message:

![Alt error](./error.png?raw=true "Error")
