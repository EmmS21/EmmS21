# Emmanuel Sibanda

Software Engineer focused on building production systems that automate workflows and reduce infrastructure costs.

## Where to place me

- Forward Deployed Engineer: embed with the people doing the work, find the bottleneck, ship the workflow, stay through adoption. Blackstone consultants. Dagger presentations into team use.
- Solutions Engineer: earn trust with a technical buyer, show the product in their problem, isolate the failure, ship the fix. GizmoSQL visualization and simulations into a contract. GrowthBook implementor confusion. Dagger Commander.
- Product Engineer: start from who the product is for, isolate the class of failure, ship the smallest fix that protects the end user. GizmoSQL product gap from simulations. CHT duplicate SMS. Plausible import purge. Koza volume guardrails.
- Founding Engineer: own discovery through deployment on a small team, multiple hats. FundaAI laptop stack. AdAlchemy agent pipeline. GizmoSQL contract.
- Backend: production APIs, data pipelines, and infrastructure. Blackstone FastAPI agents, Snowflake to RDS, Terraform disaster recovery, GitLab CI/CD.

## What I Do

- Backend and AI workflows (Python: FastAPI, Django, Flask; JavaScript: Node.js; LangChain; multi-agent systems)
- Data pipelines and migrations (AWS Step Functions, ETL, RDS, Snowflake, PostgreSQL)
- Infrastructure (Terraform, GitLab CI/CD, cloud cost control)

## Selected Work

### Blackstone, AI Systems and Infrastructure

- Built multi-agent AI APIs on unstructured data, enabling automated reporting, note-taking, and queryable insights for internal consultants
- Designed the Snowflake-to-RDS migration using AWS Lambda and Step Functions, with cursor-based pagination and dependency-aware ordering
- Optimized PostgreSQL (connection pooling, indexing) after moving relational reporting off the warehouse, lowering AWS spend by six figures annually
- Built a Terraform-managed disaster recovery system using cross-region AWS Backup replication, with RTO/RPO defined and no always-on standby cost
- Standardized CI/CD across teams using GitLab runners and Terraform provisioning

## Open Source

### Dagger

- Built and published containerized pipeline modules: weekly financial advice by SMS, AI unit-test generation, and AI school workflows
- Presented these use cases, drove adoption on my team at Blackstone to orchestrate pipelines faster, and was selected as a Dagger Commander
- Isolated a class of setup failures behind corporate proxies and shipped the docs fix upstream. Followed with a mental-model issue and docs so gated environments stop configuring the laptop and failing before the pipeline runs

### FundaAI

Offline-first AI education system using local LLMs, vector embeddings, and distributed content pipelines.

- Built device auth, content distribution, AI tutors, and the embeddings pipeline that turns Drive PDFs into retrievable vector content
- Linux, Shell, Python, Go, React, PySide6, Electron, SQL

### GizmoSQL

- Capped how many clients can sit on a shared server at once, and cleaned up quiet connections so abandoned sessions do not fill the box
- Built an interactive visualization of why a local database lock breaks shared access, and what the shared server changes
- Tested the product by running warehouse simulations. Found a gap: if you kill the client mid-query, the heavy query keeps running on the server. This work led to a contract with GizmoData

### GrowthBook

- Two experiments could look like one in analytics because the app only sent the human-readable name
- Teams thought turning on a sync setting would keep flags up to date. It did not. Shipped an opt-in so analytics can tell experiments apart, and docs so implementors stop assuming the cache refreshes itself


## Selected Projects

### AdAlchemyAI

LangChain multi-agent system orchestrated on AWS (Lambda, Step Functions, SQS). Automated marketing workflows for 3 small businesses in New York.

## Contact

emmanuel@emmanuelsibanda.com
