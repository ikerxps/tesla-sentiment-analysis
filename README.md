# Tesla Brand Sentiment Analysis

Brand sentiment research project analysing 10,000+ Reddit posts to identify 
audience perception patterns around Tesla. Built as a team project at the 
University of Europe for Applied Sciences, Berlin.

## Overview

This project delivers a full end-to-end data pipeline — from raw Reddit data 
ingestion to interactive Tableau dashboards — to surface actionable brand 
insights from social media at scale.

## What it does

- Collects Reddit posts via the PRAW API (Python)
- Processes and cleans raw text using Hadoop MapReduce
- Performs sentiment classification using Python and VADER
- Stores and queries structured data with SQL
- Visualises results across 6 interactive Tableau dashboards

## Key findings

- Identified 3 statistically distinct audience sentiment segments
- Reduced manual data cleaning time ~60% through MapReduce preprocessing
- Consistent polarity classification across the full 10,000+ post corpus

## Tech stack

| Tool | Purpose |
|------|---------|
| Python / PRAW | Reddit API data ingestion |
| Hadoop / MapReduce | Large-scale text preprocessing |
| SQL | Data querying and EDA |
| VADER | Sentiment scoring |
| Tableau | Dashboard visualisation |

## Project structure
