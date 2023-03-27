# ChatGPT-Excel Integration
This is a modified version of adding ChatGPT to Excel using JavaScript based on LG-Experiment's OpenAI.ts
[original link](https://github.com/LG-Experiment/Scripts/tree/main/OpenAI%20in%20Excel%20Script)

The purpose of this doc is to solve the ERROR `Line 46: Cannot read properties of undefined (reading '0')` from the original code

  **Here are some actions you could take if you are experiencing undefined properties issue:**
  
  1. Create and use a new API key
  2. Check if your API usage is above the limit
  3. Change the endpoint and model, reference: https://platform.openai.com/docs/models/gpt-3
    
    `const endpoint: string = "https://api.openai.com/v1/completions";`
    
    `const model: string = "text-davinci-003";`
  

Highly recommend to watch the high quality video made by Leila Gharani: https://youtu.be/kQPUWryXwag
