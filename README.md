# AWS Visitor Counter

This is a simple web application built using AWS services to track the 
number of visitors to a page.

## Technologies Used:
- AWS Lambda
- API Gateway
- DynamoDB
- S3
- CloudFront

## How It Works:
The application uses AWS Lambda to handle API requests and updates a 
DynamoDB table to track the number of visitors. The count is displayed on 
the webpage, and each time the page is refreshed, the visitor count is 
incremented.

## Setup Instructions:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/aws-visitor-counter.git

