Agentic AI Weather Assistant using Amazon Bedrock

This project demonstrates how to build a simple Agentic AI system from scratch using Python and the AWS SDK without relying on complex frameworks. The agent interacts with Amazon Bedrock (Claude Sonnet) to reason about user requests, generate API calls, and summarize real-time weather information.

The system integrates with the National Weather Service (NWS) API to retrieve live weather data and transform raw JSON responses into clear and useful forecasts.

Key Capabilities

The AI agent demonstrates core Agentic AI principles:

Thinking

Uses Claude Sonnet via Amazon Bedrock to analyze location queries

Determines coordinates and generates appropriate API calls

Acting

Calls the National Weather Service API to retrieve forecast data

Processing

Parses and analyzes complex JSON weather data

Responding

Converts raw weather data into clear, human-readable summaries

Features

Command-line AI agent

Web interface built with Streamlit

Integration with Amazon Bedrock

Real-time weather data retrieval

Dynamic API generation using AI reasoning

Architecture

The agent follows a simple agentic workflow:

User Input → AI Planning → NWS Points API → Forecast API → AI Processing → Weather Summary
Technologies Used

Python

Amazon Bedrock

Claude Sonnet

AWS SDK (boto3)

Streamlit

National Weather Service API

Learning Goals

This project demonstrates:

Building Agentic AI systems without frameworks

Integrating LLMs with external APIs

Using Amazon Bedrock for AI reasoning

Creating both CLI and web-based AI applications
