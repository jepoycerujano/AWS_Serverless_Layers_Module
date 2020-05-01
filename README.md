# AWS_Serverless_Layers_Module
AWS Serverless Layer was created to used all dependencies module in all our Lambda Function. 

How to used and deploy?

```
1. open git bash or command prompt
2. navigate to AWS_Serverless_Layer_Module
3. npm install
4. navigate to layer_modules folder
5. npm install 
6. navigate back to AWS_Serverless_Layer_Module 
7. sls deploy
```
### IMPORTANT: add to your lambdas environment NODE_PATH: './:/opt/node_modules' see Examplae: AWS_Serverless_DynamoDb_CRUD (https://github.com/jepoycerujano/AWS_Serverless_DynamoDb_CRUD)