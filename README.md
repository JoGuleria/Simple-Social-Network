# Simple-Social-Network
# Simulating Social Media Network Structures with Python

This project models a simplified social media network using Python’s `networkx` library, as part of an academic exercise in the Social Media & Text Analytics course at the University of Rochester. It demonstrates how social interactions—such as replies, mentions, or follows—can be modeled as directed graphs, forming the structural foundation of many modern text analytics pipelines.

##  Objective

- Represent social media interactions as directed network graphs.
- Visualize asymmetric relationships between users (nodes).
- Build graph structures using both adjacency lists and matrices.
- Lay groundwork for future applications in text analytics and NLP.

##  Project Description

The network includes five users: Joe, Molly, Harini, Renuka, and Lijuan. Directed edges indicate one-way interactions such as a user mentioning or replying to another. The relationships were constructed in three formats:
- **Adjacency List**
- **Adjacency Matrix**
- **Edge List**

The network was visualized using `matplotlib` and optionally rendered as an **interactive HTML dashboard** using `pyvis`, simulating behavior similar to platforms like Twitter or Reddit.

While the dataset is fictional, the methodology mirrors real-world analysis — providing foundational exposure to network-based insights like influence mapping, community detection, and engagement flow.

## Tools Used

- **Python 3**
- **NetworkX** – for graph creation and manipulation
- **Matplotlib** – for static network visualization
- **NumPy** – for matrix construction
  
