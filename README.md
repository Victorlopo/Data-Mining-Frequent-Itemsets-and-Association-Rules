# Frequent Itemset Mining & Association Rule Generation with A-Priori Algorithm

## Introduction

In the realm of market basket analysis, discovering patterns and relationships between items in large datasets is crucial for decision-making and strategy development. My project tackles this challenge by implementing the A-Priori algorithm to mine frequent itemsets and generate association rules from a dataset of sales transactions. This implementation showcases the practical application of data mining techniques in identifying itemsets with significant support and deriving rules with high confidence.

## Project Overview

This project is structured into two main components:

### Frequent Itemset Mining

The first component involves developing an implementation of the A-Priori algorithm to identify frequent itemsets within a sales transaction dataset. The goal is to find all itemsets that appear in at least `s` transactions, where `s` is a predefined support threshold.

### Association Rule Generation

Building on the frequent itemsets identified, the second component focuses on generating association rules that meet specific support (`s`) and confidence (`c`) criteria. This step aims to uncover meaningful relationships between items, providing insights into customer purchasing patterns.

## Dataset

The analysis is performed on a dataset containing hashed sales transactions. Each transaction represents a basket of items purchased together.


