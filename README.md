# Intelligent Chatbot with Context Retention and Human-like Responses

Welcome to our Intelligent Chatbot project! This chatbot is designed to retain context from previous chats, allowing it to answer related questions and maintain a smooth conversational flow effectively. With error handling in place, the chatbot aims to provide human-like responses and ensure a delightful user experience.

## Table of Contents
- [Introduction](#introduction)
- [Instructions](#instructions)
- [Usage](#usage)
- [Features](#features)

## Introduction
This chatbot is built on top of the GPT API and incorporates various instruction prompts to enhance its capabilities. It effectively identifies whether a given prompt is a statement or a question and stores statements for future reference. It also optimizes question analysis by identifying whether a question is independent or dependent on previous context, which helps reduce redundant checks.

## Instructions
The chatbot utilizes four instruction prompts:

1. **Statement or Question Detection**: This prompt determines whether the user's input is a statement or a question. If it is a statement, the chatbot stores it for use in the conversation.

2. **Independent or Dependent Question Analysis**: The chatbot identifies whether a question is independent or dependent on previous context. This step streamlines processing, ensuring efficient handling of questions.

3. **Identifying Relevant Context**: The chatbot analyzes the question to determine its relevance to previous chat messages. It finds the appropriate context or chat message to which the question is related.

4. **Generating the Response**: Based on the context or previous chat message, the chatbot generates a response to provide an informative and relevant answer.

## Usage
To interact with the chatbot, simply input your message or question. The chatbot will analyze the instruction prompts and respond accordingly. It will use its contextual memory to answer questions related to previous conversations.

## Features
- Context Retention: The chatbot stores statements from previous chats to maintain context throughout the conversation.
- Efficient Question Analysis: The chatbot identifies whether a question relies on previous context, optimizing its responses for a smoother interaction.
- Relevant Context Identification: The chatbot determines the context or chat message to which a question is related, ensuring accurate responses.
- Human-like Responses: With careful instruction prompts and error handling, the chatbot aims to provide responses that mimic human conversation.


