# Chat-Bot-Web-Application
Support Agent Chatbot for CDP
Developed a chatbot that can answer "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot should be able to extract relevant information from the official documentation of these CDPs to guide users on how to perform tasks or achieve specific outcomes within each platform.
# CDP Support Agent Chatbot

A chatbot that answers "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap.

## Features

- Answers "how-to" questions about CDP platforms
- Extracts information from official documentation
- Handles variations in question phrasing
- Provides cross-CDP comparisons
- Responds to advanced "how-to" questions

## Data Sources

The chatbot uses data extracted from the following documentation sources:

- Segment Documentation: https://segment.com/docs/
- mParticle Documentation: https://docs.mparticle.com/
- Lytics Documentation: https://docs.lytics.com/
- Zeotap Documentation: https://docs.zeotap.com/home/en-us/

## Implementation

The chatbot uses a combination of:

1. **Data Extraction**: A script to extract content from CDP documentation
2. **Question Analysis**: Functions to determine which CDP the question is about
3. **Document Search**: A simple search algorithm to find relevant documentation
4. **Response Generation**: Logic to format responses based on search results

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm run dev
   ```

3. Extract documentation (optional, as sample data is included):
   ```
   npm run extract
   ```

## Example Questions

- "How do I set up a new source in Segment?"
- "How can I create a user profile in mParticle?"
- "How do I build an audience segment in Lytics?"
- "How can I integrate my data with Zeotap?"
- "How does Segment's audience creation process compare to Lytics'?"

## Project Structure

- `src/components/`: React components for the chat interface
- `src/utils/`: Utility functions for documentation search and response generation
- `src/data/`: Extracted documentation data
- `scripts/`: Data extraction scripts

LINK: https://sprightly-semifreddo-0d8b21.netlify.app/

ScreenShots

![Screenshot 2025-03-01 212916](https://github.com/user-attachments/assets/31f89270-9330-4fcf-9e79-7b8789f5c7bc)
![Screenshot 2025-03-01 212851](https://github.com/user-attachments/assets/a2aba97a-e04f-4b97-acb1-612479a9a696)

