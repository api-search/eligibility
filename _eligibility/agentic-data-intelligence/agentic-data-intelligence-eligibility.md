---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Customer is not located in, resident in, or organised under the laws of any country or territory that is (i) subject to comprehensive sanctions or embargoes administered by the European Union (EU), the Swiss State Secretariat for Economic Affairs (SECO), or the US Office of Foreign Assets Control (OFAC)
  entity_types:
  - text: If a natural person, the Customer is over the age of 18 and eligible to enter into the Agreement and use the Services.
    type: individual
  minimum_age:
    text: If a natural person, the Customer is over the age of 18
    value: '18'
  restricted_uses:
  - summary: High-risk AI system use
    text: The Customer shall not use the Services, or permit them to be used, in a way that would make the Services a high-risk AI system under Regulation (EU) 2024/1689 (the EU AI Act)
  - summary: Critical infrastructure operation
    text: The Customer is not, and is not acting on behalf of, an operator of critical infrastructure, and that the Services will not be used in or in connection with the operation of critical infrastructure.
  - summary: Circumventing restrictions with VPNs
    text: The Customer does not use Virtual Private Network software or any other privacy or anonymization tool or technique to circumvent any restrictions which apply to the Services.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Company may subject the full access of a Customer to the Services to its prior approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agentic Data Intelligence
provenance_date: '2026-11-09'
provider_name: Agentic Data Intelligence
provider_slug: agentic-data-intelligence
slug: agentic-data-intelligence-eligibility
source_date: '2026-11-09'
source_filename: agentic-data-intelligence-eligibility.yml
source_heading: Eligibility
source_page: https://agentic-data.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentic Data Intelligence\naid: agentic-data-intelligence\nurl: https://agentic-data.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Customer is not located in, resident in, or organised under the laws of any country or territory that\n    is (i) subject to comprehensive sanctions or embargoes administered by the European Union (EU), the Swiss State\n    Secretariat for Economic Affairs (SECO), or the US Office of Foreign Assets Control (OFAC)\nentity_types:\n- type: individual\n  text: If a natural person, the Customer is over the age of 18 and eligible to enter into\
  \ the Agreement and use\n    the Services.\nrestricted_uses:\n- summary: High-risk AI system use\n  text: The Customer shall not use the Services, or permit them to be used, in a way that would make the Services\n    a high-risk AI system under Regulation (EU) 2024/1689 (the EU AI Act)\n- summary: Critical infrastructure operation\n  text: The Customer is not, and is not acting on behalf of, an operator of critical infrastructure, and that the\n    Services will not be used in or in connection with the operation of critical infrastructure.\n- summary: Circumventing restrictions with VPNs\n  text: The Customer does not use Virtual Private Network software or any other privacy or anonymization tool or\n    technique to circumvent any restrictions which apply to the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Company may subject the full access of a Customer to the Services to its prior approval.\nminimum_age:\n  value: '18'\n  text: If a natural\
  \ person, the Customer is over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/agentic-data-intelligence/eligibility/agentic-data-intelligence-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Agentic Data Intelligence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data Analytics
- Agents
- MCP
- Agent Skills
- Semantics
- Data Governance
- Semantic Layer
- Data Intelligence
---
