# Whatsapp_chat_analyser
This repository contains a Python script that performs an in-depth analysis of a WhatsApp group chat. The analysis includes various statistical measures, such as message count, word count, emoji usage, and activity patterns, visualized through different plots.

Overview

The script processes a WhatsApp chat exported as a .txt file, extracts relevant information, and performs several analyses. It includes:

Message and Member Analysis:

Counts the total number of messages sent.
Computes the number of words and letters per message.
Truncates phone numbers to ensure privacy.
Extracts and analyzes emoji usage.

Activity Analysis:

Identifies the most active days and times.
Determines the most active members.
Analyzes the progression of messages over time.

Visualization:

Bar charts and pie charts to visualize the frequency of messages, words, and emojis.
Line plots to show messaging trends over time.

Features

Message Statistics: Calculate total messages, words, and letters. Average words per message are computed per member.
Emoji Analysis: Extracts emojis from messages and counts their usage.
Activity Patterns: Identifies the most active days, times, and members.
Word Frequency: Analyzes and visualizes the most common words used in the chat, excluding media messages.
Progression of Messages: Visualizes how the number of messages sent evolves over time.

Installation

Requirements
Python 3.x
Pandas
Numpy
Matplotlib
Plotly
Regex

Usage
Prepare Your WhatsApp Chat Export:

Export the WhatsApp group chat as a .txt file and place it in the same directory as the script.
Run the Script:

Execute the script to generate the analysis and visualizations.
The script reads the chat file, processes the data, and outputs various statistics and visualizations.
Analyze the Output:

The script prints statistics for each member and displays plots for the most active days, times, members, and word frequency.

Note:
Replace chatfile1.txt with your actual WhatsApp chat filename in the script before running it.
