# netlify_lambda
# Example of Netlify Lambda function
[build]
  command = "npm run build"
  functions = "lambda" #  netlify-lambda reads this
  publish = "build"
