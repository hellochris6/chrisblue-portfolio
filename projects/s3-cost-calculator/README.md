#### S3 Glacier Restore Cost Calculator

#### Context
- Role: FinOps / Cloud Operations Engineer
- Objective: Built a tool to accurately estimate and optionally track AWS S3 Glacier data restoration costs.

#### Problem
Challenge: Complex S3 Glacier pricing led to unpredictable retrieval bills and hindered financial planning.

Data: Lack of cost visibility caused budgeting challenges and audit difficulties.

#### Action
Process: Developed an interactive shell script (bash, bc, curl) to estimate costs based on object size/count, supporting Standard/Bulk options.

Contribution: Automated on-demand cost estimation; integrated optional Airtable logging for finance/audit.

Seniority: Proactively solved a critical FinOps transparency problem, empowering users and improving financial tracking.

#### Result
Solution: Accurate, real-time AWS S3 Glacier restoration cost estimates.

Impact: Enabled predictable costs, reduced financial surprises, and streamlined data retrieval decisions.

Value: Improved financial predictability and auditability of cloud expenditures.

#### Final Product
An interactive shell script for S3 Glacier cost estimation and tracking, deployable on Unix-like systems.
