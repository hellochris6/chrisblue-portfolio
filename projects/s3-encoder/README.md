#### S3 Manifest Key Encoder (Python Script)

#### Context
- Role: Data Engineer / Solutions Developer
- Objective: Automate S3 object key encoding for batch operations, resolving a critical technical support gap.

#### Problem
- Challenge: S3 batch operations failed due to unaddressed URL encoding requirements for object keys, a high-level issue technical support couldn't resolve.
- Data: Frequent operation failures and workflow delays caused by incorrect key encoding.

#### Action
- Process: Developed a Python script to read CSV input, URL-encode S3 object keys (urllib.parse.quote), and output a new encoded CSV.
- Contribution: Independently designed and implemented a self-contained solution, requiring no external dependencies.
- Seniority: Identified and resolved a critical operational bottleneck, delivering a targeted utility to unblock essential data workflows.

#### Result
- Solution: A reliable Python script for automated S3 object key URL encoding in manifest files.
- Impact: Eliminated encoding errors, enabling consistent and reliable S3 batch operations.
- Value: Streamlined data workflows, prevented data integrity issues, and removed a key technical barrier.

#### Final Product
- A ready-to-use Python script (s3_key_encoder.py) generating compliant encoded CSV manifest files.
