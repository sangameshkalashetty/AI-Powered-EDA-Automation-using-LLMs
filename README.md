# AI-Powered-EDA-Automation-using-LLMs

# Overview

This repository contains code for a machine learning project that performs automated Exploratory Data Analysis (EDA) on uploaded CSV files. The project leverages libraries like Pandas, Matplotlib, Seaborn, and Ollama to generate data summaries, visualizations, and AI-powered insights, aiming to provide a comprehensive EDA report for any given dataset. The core of the tool is a Gradio interface that allows users to upload a CSV and receive an automated EDA analysis.

# Abstract

This project uses machine learning and data visualization techniques to automate EDA, providing users with automated insights and visualizations from any CSV dataset. The project integrates AI insights generated by Ollama's Mistral model, providing more context for EDA

# Introduction

The goal is to develop a tool that automates the exploratory data analysis process on any given dataset CSV file. This involves automatically handling missing values, generating descriptive statistics, visualizing data distributions, and providing AI-powered insights, improving the efficiency of data analysis.

# Problem Statement

Develop an automated EDA tool that streamlines the initial data exploration process, providing users with key insights and visualizations to quickly understand the structure and characteristics of their data.

# Motivation

**Automated EDA:** Streamlines the process for quicker analysis.

**AI-Powered Insights:** Enhance understanding with AI-generated analyses.

**Comprehensive Reporting:** Detailed summaries, missing values reports, and AI interpretations.

**Visualizations:** Generates data distribution histograms and correlation heatmaps.

**User-Friendly Interface:** Intuitive Gradio interface for easy upload and analysis.

**Data Cleaning:** Automatically handles missing values with median/mode imputation.

**Accessibility:** Shareable Gradio app provides broader accessibility.

**Efficiency:** reduces time needed for initial data exploration

**Scalability:** easily scalable to larger datasets

# Key Points

**Data Loading and Preprocessing:** Loads CSV data using Pandas, handles missing values by imputing with median for numeric columns and mode for categorical columns.

**Data Summary Generation:** Computes descriptive statistics using df.describe(include='all') and formats it into a string. Also reports counts of missing values.

**AI-Powered Insights:** Integrates Ollama's Mistral model via ollama.chat to generate insights based on the data summary.

**Data Visualization:** Generates histograms for numeric columns using Matplotlib and Seaborn and a correlation heatmap for numeric columns.

**Gradio Interface:** Creates a Gradio interface with gr.Interface for easy file upload and display of the EDA report and visualizations.

**Automated Reporting:** Generates a comprehensive text report including data summary, missing values, and AI insights.

**Shareable Application:** Launches the Gradio app with share=True for easy sharing and accessibility.

# Key changes and explanations:

**Focus on Automation:** The text emphasizes the automated nature of the EDA.

**Specific Libraries Mentioned:** Pandas, Seaborn, Matplotlib, and Ollama are specifically named.

**AI Integration Highlighted:** Ollama's role in generating insights is mentioned prominently.

**Input/Output Description:** The CSV upload and the generated report are described.

**EDA Tasks Outlined:** Steps like handling missing values, generating statistics, and visualizing data are explicitly mentioned.

**Emphasis on User-Friendliness:** The Gradio interface is highlighted.

**Metrics Changed:** There's no model evaluation in the sense of prediction accuracy, so that section is removed.

**Imputation Method:** Describes how missing values are handled
