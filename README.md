## Problem

We have the text of a chat conversation where a person talks about their favorite song. 
We want our application to extract the names of the song and the singer and store them in JSON format.

## Solution

- Use `ResponseSchema` to determine the data we want to extract.
- Use an `OutputParser` from LangChain to extract the data.

## Process

1. Use `ResponseSchema` to determine the data we want to extract.
2. Use `StructuredOutputParser` to store the extracted data in a JSON dictionary.
3. Create the `ChatPromptTemplate`.
4. Input the user's message.
5. Extract the data and store it in JSON format.
