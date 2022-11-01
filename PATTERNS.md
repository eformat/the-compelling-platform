# Patterns for the Compelling Platform

_"An antipattern is a solution that initially looks like an attractive road lined with flowers ... but further on leads you into a maze filled with monsters"_ - Martin Fowler.

> The platform is the _thinnest viable_

- Not boiling the ocean
- Platform evolution
- Measuring success

> The platform is composable, containing discrete services that can be used independently.

- Open Hybrid Cloud - Multi-tenancy, Multi-cluster, Multi-cloud
- Multi-tenancy & Isolation
- Use of Operators
    - cluster vs namespaced resources
- Composing and configuring the platform applications
  - GitOps
    - choosing the right controller
    - scaling gitops with folders
    - repository structures (infra, cluster-scoped, platform apps)
    - helm / kustomize
    - ubiquitous-journey, app-of-apps pattern

> The platform is self-service for the overwhelming majority of use cases.

- Team and User On-Boarding workflow
- Namespace Provisioning
- DevEx & UX
  - personas
  - accessing the platform

> The platform does not force an inflexible way of working upon the delivery team.

- You build it, You ship it, You run it, You own it
- Any workload, any cloud
- We prefer Lean Agile to Waterfall delivery
- The use of SaaS

> The platform is quick and cheap to start using, with an easy on-ramp (e.g. Quick start guides, documentation, code samples)

- Safe places to fail are designed in
- Costs - Charge-back, show-back - part of team on-boarding
- What nobody tells you about documentation - The Grand Unified Theory of Documentation
- Internal Developer Platforms
  - Backstage
  - Designing Golden Paths

> The platform has a rich internal user community for sharing

- Continuous Learning by sharing and collaboration
- Communities of Practice
- Scaling the Practice of Architecture, Conversationally, Evolutionary
  - Decision Record
  - Advisory Forum
  - Team-sourced Principles
  - Roadmaps / Technology Radar
  - Application Patterns
    - Monoliths
    - Microservices
    - Stateful Serverless
    - Streaming
    - AIML
    - Edge Patterns

> The platform is secure and compliant by default

- Continuous Compliance
- Moving Security Left
- Secure Supply Chain
- Secrets Management
  - Tenant ArgoCD & Vault
- Identity and Access Management for All
  - integrated SSO

> The platform is up to date

- In-place upgrades
- CI/CD - Pipelines and Quality Control
- Installing the base platform in any cloud in a sustainable manner
  - Ansible / Terraform
  - Zero Touch Provisioning
  - Crossplane
- Trusted Vendors
  - undifferentiated heavy lifting
- Monitoring & Metrics
