---
title: "README"
author: "Callum Magarian"
date: "2026-10-25"
output: html_document
---

# Genre Similarity in the Genius Follower Network

## Overview

This project seeks to determine whether Genius users who annotate similiar musical genres are more likely to follow each other. This will be analyzed through robust subsetting, network sampling methods and how differences between them affect network attributes and overall effectiveness. 

## Research Questions

1. Does the similarity between genre and profile impact the formation of the network?
2. Do these conclusions hold up against sampling with different network designs?
3. Does the genre of music a user interacts with drive specific connections? 
4. Do results change based on the sampling algorithm we choose? 

## Data and Network

We are using the Genius dataset that was used in Cornell research: *Expertise and Dynamics within
Crowdsourced Musical Knowledge Curation: A Case Study of the Genius Platform* by Derek Lim and Austin R. Benson.
- Nodes: Genius users with sufficient annotation data to construct their genre profiles
- Edges: Directed follower relationships, where an edge from user i to user j means that i follows j
- User attributes: Genre profiles that are derived from songs that users annotate and measurements relating to their Genius contributions

Dataset and original research code: https://github.com/cptq/genius-expertise

## Planned Analysis

lets iron this out in a bit

## Software

We are conducting analysis using R and RMarkdown in RStudio. We will document required packages and instructions as needed throughout the project.

## Project Status

We are actively working on the initial setup and exploratory data analysis.