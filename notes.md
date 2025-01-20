  ### **Literature Review**
  #### **1. Introduction**
  - Briefly outline the purpose of the literature review.
  - Highlight the main areas of focus and their relevance to your thesis.
  - Explain the relationship between the reviewed topics and your research objectives.

  ---

  #### **2. Epidemics: Historical and Conceptual Overview**
  - **Definition and Impact**: Define epidemics and their societal, economic, and health impacts.
  - **Historical Context**: Briefly discuss notable epidemics (e.g., Black Death, Spanish Flu, COVID-19).
  - **Complexities in Epidemic Dynamics**: Highlight spatial, temporal, and social factors influencing disease spread.

  ---

  #### **3. Epidemic Forecasting**
  - **3.1 Traditional Methods**
    - Overview of non-machine learning methods like SEIR, agent-based models, and statistical approaches.
    - Limitations: Simplifying assumptions, difficulty incorporating spatial/temporal data, and real-time adaptability challenges.
    
  - **3.2 Machine Learning-Based Methods**
    - Key machine learning approaches (e.g., LSTMs, random forests, reinforcement learning).
    - Strengths and limitations in real-world epidemic forecasting.
    - Mention the lack of domain transferability and adaptability to sparse data in certain approaches.

  ---

  #### **4. Graph Neural Networks (GNNs)**
  - **4.1 Overview of GNNs**
    - Introduction to GNNs and their architecture.
    - Key concepts: Message passing, node embeddings, and aggregation functions.
    - Popular GNN variants: GCN, GraphSAGE, GAT, etc., and their applications.
    
  - **4.2 Applications of GNNs in Epidemic Forecasting**
    - Discussion of how GNNs handle spatio-temporal dependencies and graph-structured data.
    - Examples of studies utilizing GNNs for modeling infectious disease spread.
    - Advantages of GNNs over other methods (e.g., incorporation of spatial networks, flexibility with heterogeneous data).

  ---

  #### **5. Transfer Learning**
  - **5.1 Overview of Transfer Learning**
    - Definition, motivation, and fundamental types (e.g., domain adaptation, cross-task transfer).
    - The importance of Transfer Learning in handling data-scarce scenarios.
    
  - **5.2 Transfer Learning in GNNs**
    - How Transfer Learning is applied in graph neural networks.
    - Challenges: Domain shifts, graph-specific adaptations, and hyperparameter tuning.
    - Examples from other fields, e.g., chemistry, social networks, and biology.

  ---

  #### **6. Existing Paper on GNN-Based Epidemic Forecasting in New Zealand**
  - **6.1 Overview of the Study**
    - Detailed summary of the methodology, data, and results from the paper.
    - Key innovations, such as their use of spatio-temporal GNNs and integration of socioeconomic/geographic data.
    
  - **6.2 Lessons and Inspiration for Your Thesis**
    - Discuss how this paper influenced your approach.
    - Highlight the specific methods or techniques from the paper that you aim to adapt or improve for the Cuban context.

  ---

  #### **7. Identified Gaps and Research Opportunities**
  - Synthesize gaps in the reviewed literature:
    - Limited studies focusing on epidemic forecasting in low-resource, geographically isolated countries like Cuba.
    - Few applications of Transfer Learning for epidemic modeling using GNNs.
    - Limited integration of localized socio-demographic data in GNN-based models.
    
  - Position your thesis as addressing these gaps.