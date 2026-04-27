# FairAI+

FairAI+ is a web application designed to detect and analyze bias in hiring decisions using AI-powered tools. It helps organizations ensure fairness in their recruitment processes by evaluating datasets for gender-based bias and providing actionable insights.

## Overview

In today's world, AI systems can inadvertently perpetuate biases present in training data, leading to unfair outcomes in hiring, lending, and other decision-making processes. FairAI+ addresses this by allowing users to upload hiring data (e.g., CSV files), analyze it for bias, and receive a fairness score along with AI-generated explanations and suggestions to mitigate bias.

The application consists of a `React`-based frontend for user interaction and a `Node.js` backend that handles data processing, bias calculation, and AI integration using Google's Generative AI.

## How It Works

1. **Data Upload**: Users upload a CSV file containing hiring data, including columns for gender and selection status.
2. **Bias Analysis**: The backend processes the data using a bias calculator that computes selection rates for different gender groups and generates a fairness score.
3. **AI Insights**: Integrated AI (`Google Gemini`) provides explanations of detected bias and suggests ways to reduce it.
4. **Visualization**: Results are displayed on a dashboard with charts and metrics for easy interpretation.

## Features

-User uploads dataset (CSV)
-System analyzes group-wise data
-Bias detection algorithm runs
-Fairness score is generated
-Bar chart visualization is displayed
-AI explains bias in simple terms
-AI suggests improvements

## Tech Stack
**Frontend**: React.js
**Backend**: Node.js express
**AI Integration**: Gemini API
**Visualization**: Chart.js 

## Repository

**Backend Repo** : 
https://github.com/riyahardia784/fair-ai-backend.git

**Frontend Repo**:
https://github.com/riyahardia784/fair-ai-frontend.git

## Live link 
https://fair-ai-git-main-riyahardia252-3519s-projects.vercel.app

## License
This project is licensed under the MIT License.
