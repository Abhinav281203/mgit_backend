# OpenAI Function Calling for Elderly Care

This project showcases how OpenAI's function calling can be applied to elderly care, helping senior citizens who may only be able to type messages. 

With this API, The model works 2-ways
*  Provides straightforward text-based replies.
*  Decides to execute a function with necessary arguments.

We can describe the functions, and the model smartly generates a JSON object with the needed arguments to call those functions from natural language in the desired format the function expects and also tell which function should be called according to the situation. The API doesn’t actually call the functions; This tool is ideal for creating assistants that utilize APIs, convert natural language into API calls, or extract structured data effectively.
