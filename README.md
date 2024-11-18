# Process Mining with Real World Financial Loan Applications: Improving Inference on Incomplete Events

<strong> Discovering and Evaluating Process Models Using PM4Py and Scikit-Learn </strong>

The financial sector often grapples with complex processes involving large datasets that record every step of business operations. One such domain is loan application processing, where event logs capture the interactions between customers and institutions. However, these event logs are frequently incomplete, leading to challenges in understanding, optimizing, and validating business processes. This project addresses these issues by leveraging process mining techniques and machine learning to analyze real-world financial loan applications.

By adopting open-source tools such as PM4Py and Scikit-Learn, this project not only replicates traditional methodologies but also extends them to uncover deeper insights. The goal is to improve process inference, even with incomplete or noisy event data, and provide actionable recommendations to enhance efficiency and compliance.

This project is inspired by and builds upon the methodologies presented in the following paper:</br>
*Analyzing Application Process for a Personal Loan or Overdraft of Dutch Financial Institute with Process Mining Techniques*
**Chang Jae Kang et al.**

## Project Overview

This project begins with a real-world dataset of financial loan applications. Each application represents a unique case, consisting of sequential events such as "Application Submitted," "Document Validation," and "Loan Approved or Declined." These events are captured in an event log, providing a rich source of information to explore and optimize the underlying business processes.

The first step involves preparing the dataset by cleaning, transforming, and standardizing the data. Missing values in resource allocations, timestamps, and activity attributes are carefully handled to ensure consistency. The data is then enriched with statistical and categorical insights, setting the stage for detailed analysis.

Process mining techniques are applied to discover hidden patterns and relationships within the data. Activities are mapped to simplified representations to enable efficient visualization and analysis. By concatenating activity sequences for each case, the project identifies common pathways and deviations. Key points of interest include the most frequent starting and ending activities and the transitions that contribute to bottlenecks.

To delve deeper, the project employs clustering algorithms to group cases with similar behavior. This helps identify patterns among successful loan applications and highlights problematic cases for targeted improvements. The insights gained here are critical for designing more efficient workflows and improving customer experience.

Visual analytics play a significant role in this project. Using tools like Graphviz, dependency graphs and directly-follow graphs are generated to illustrate relationships between activities. These visualizations help stakeholders intuitively understand the flow of processes, pinpoint inefficiencies, and validate compliance with organizational standards.

The project's final phase focuses on deriving actionable recommendations. By combining the insights from process mining, clustering, and conformance checking, strategies for optimizing loan application workflows are proposed. These strategies aim to reduce processing times, improve compliance, and enhance overall efficiency.

## Key Highlights

### Real-World Application
The project uses real-world financial data, focusing on the practical challenges of incomplete event logs and noisy data. This ensures the methodologies are robust and scalable for real-world scenarios.

### Advanced Analysis
From process discovery and conformance checking to clustering and dependency analysis, the project employs a wide range of techniques to extract actionable insights.

### Open-Source Tools
Unlike traditional approaches that rely on proprietary software, this project demonstrates the power of open-source Python libraries. PM4Py and Scikit-Learn are used to replicate and enhance methodologies previously dominated by commercial tools.

## Goals and Outcomes

1. **Process Discovery**:
   - Identify common workflows, deviations, and bottlenecks.
   - Map activities to simplified representations for efficient analysis.

2. **Enhanced Inference**:
   - Address the challenge of incomplete event logs.
   - Develop strategies to infer missing or ambiguous data points.

3. **Optimization**:
   - Propose actionable recommendations to reduce processing time and improve compliance.

4. **Visual Understanding**:
   - Create intuitive graphs to help stakeholders visualize and validate process flows.

5. **Scalability**:
   - Ensure that the methodologies can be applied across diverse datasets and domains.

## Conclusion

This project bridges the gap between academic research and practical implementation in the field of process mining. By addressing real-world challenges like incomplete event logs and leveraging the accessibility of open-source tools, it provides a blueprint for enhancing business processes. The insights gained not only help optimize financial workflows but also lay the foundation for applying similar methodologies in other industries. This journey of discovery, analysis, and action serves as a valuable contribution to the growing field of process mining and business process optimization.
