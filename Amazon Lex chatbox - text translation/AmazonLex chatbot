Services Used
Amazon Lex – To build the chatbot and define the conversation flow.
AWS Lambda – To fetch book recommendations from a third-party API.
Amazon Translate – To translate input/output text.
AWS IAM – To manage secure access and permissions.

Steps Performed
1. Creating an Empty Chatbot
Started with a blank chatbot in Amazon Lex.
Defined the bot name, language, and output voice/text settings.

2. Specifying Intents and Slots
Added intents for book recommendation requests.
Created slots to capture details like book genre or language.

3. Specify Fulfillment
Configured the fulfillment option to use AWS Lambda.
Connected the intent to trigger the Lambda function.

4. Create an IAM Role
Created a new IAM role with permissions for Lex and Lambda.
Attached policies for AmazonLexFullAccess, AWSLambdaBasicExecutionRole, and TranslateReadOnly.

5. Create a Lambda Function
Wrote a Lambda function (Node.js/Python) that:
Calls a third-party book recommendation API.
Uses Amazon Translate if the user’s input/output is in a different language.
Deployed the function and attached the IAM role.

6. Test the Lambda Function
Invoked the Lambda function independently in the AWS console.
Verified correct API responses and translation.

7. Test the Chatbot
Tested the chatbot inside the Lex console.
Confirmed that intents were captured, Lambda executed, and multilingual responses worked.
