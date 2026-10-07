# **Organizational Email Network Analysis: Exploring Key Individuals and Departmental Interactions**

## **Overview**

This project utilizes Social Network Analysis (SNA) to explore an email communication network from a large European research institution, using the email-Eu-core dataset ([Paranjape, Benson, & Leskovec, 2014]). The goal is to identify key individuals, analyze departmental roles, and understand cross-department communication patterns within the organization.

Paranjape, A., Benson, A. R., & Leskovec, J. (2014). email-Eu-core network [Data set]. Stanford Network Analysis Project. https://snap.stanford.edu/data/email-Eu-core.html

## **Context**

Email networks provide valuable insights into organizational communication, revealing how information flows and which individuals play pivotal roles. By analyzing the structure of an email network, we can identify central figures who facilitate collaboration and knowledge sharing. This project applies network theory to uncover the structural and functional roles of individuals in the organization.
The dataset used for this analysis represents email communication among employees of a European research institution, and it provides a snapshot of communication patterns within the organization. The focus of the analysis is on understanding how individuals and departments are connected and which people serve as bridges between different parts of the network.

## **Objectives**

1. **Identify Key Individuals**: Use centrality measures to identify the most influential people in the email network.
2. **Understand Departmental Roles**: Determine if key individuals are concentrated in specific departments and examine the distribution of influence across departments.
3. **Analyze Cross-Department Communication**: Investigate whether key individuals bridge multiple departments or connect people within their own department.

## **Key Concepts**

1. **Social Network Analysis (SNA)**: A method used to analyze the structure of relationships within a network, focusing on the connections between individuals and the flow of information.
2. **Centrality Measures**: Metrics used to identify the most influential or central nodes (individuals) in a network, such as degree centrality, betweenness centrality, and closeness centrality.
3. **Departmental Connectivity**: Understanding how departments interact with each other within the organization and identifying individuals who facilitate cross-departmental communication.

## **Methodology**

1. **Data Preprocessing**: The dataset was cleaned and prepared for analysis, including the removal of unnecessary data and the conversion of the network into a graph structure.
2. **Network Construction**: The email communication data was used to build a directed network where nodes represent individuals and edges represent email exchanges.
3. **Centrality Analysis**: Various centrality measures were computed to identify key individuals and their roles within the network.
4. **Visualization**: The network was visualized to reveal the structure and key individuals, and departmental roles were examined based on the network's topology.

## **Results & Insights**

The analysis highlights several key individuals who play significant roles in facilitating communication across departments. These individuals serve as bridges between isolated departments and are crucial for fostering collaboration. The project provides a clear view of how information flows within the organization and the individuals who influence this flow.
