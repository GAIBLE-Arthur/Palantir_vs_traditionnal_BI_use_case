# Palantir_vs_traditionnal_BI_use_case

Traditional Business Intelligence refers to a set of tools used by data analysts and data engineers to obtain an overall view of a company’s activities.

The most common ones are SQL (for data cleaning and manipulation), traditional ETL tools (Extract, Transform, Load), and Power BI (for data visualization). This approach is effective for identifying patterns, understanding underlying mechanisms, and supporting decision-makers (e.g. executive committees, buyers within their scope) in their analysis and decision-making.

However, these tools show  limitations when it comes to actionability. While Power BI excels at reporting and visualization, it does not allow users to act directly on the real world.

In practice, building visually appealing dashboards often requires significant time and heavy code manipulation (advanced SQL queries, complex DAX expressions). When business needs are poorly understood, this frequently results in wasted effort: frameworks are built, dashboards are published, but they are neither used nor trusted for strategic decision-making.

To address this gap, Palantir introduces a shift from Passive Reporting to Active Operations. While traditional BI focuses on the What, modern operational platforms focus on the How.

1. Ontology: 

Traditional BI relies on flat tables and schemas that users must understand and mentally reconstruct. This project instead promotes an ontology-based approach:

Object-Centric Modeling:
Rather than querying Table_X_v2_final, users interact with real-world objects such as Shipment, Factory, or Employee.

Semantic Mapping:
Complex SQL transformations are mapped to business concepts and properties, allowing users to work in their own language instead of technical abstractions.

This approach reduces cognitive load, improves alignment with business reality, and bridges the gap between data and operations.

2. The Action Layer (Write-back)

The core weakness of traditional BI tools such as Power BI is their read-only nature. A robust data architecture must go beyond visualization and enable action:

Write-back Capabilities
Data-driven decisions must be pushed back into operational systems (ERP, CRM, planning tools) directly from the platform.

Simulations
Instead of reporting disruptions after they occur, users should be able to simulate scenarios (e.g. supply chain disruptions, capacity constraints) and evaluate outcomes before decisions are executed.

To assess this assumption, we are gonna treat the same problem (the case of 3 plants of the pharmaceutical sector with differents workways) using:

- Traditionnal tools ; SQL, Power BI 

- Palantir Foundry

Andiamo !
