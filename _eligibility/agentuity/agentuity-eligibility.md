---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher, to use the Services.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher, to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or rights-infringing uses
    text: Use the Services to develop applications that violate these Terms or applicable laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agentuity
provenance_date: '2026-11-09'
provider_name: Agentuity
provider_slug: agentuity
slug: agentuity-eligibility
source_date: '2026-11-09'
source_filename: agentuity-eligibility.yml
source_heading: Eligibility
source_page: https://agentcompany.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentuity\naid: agentuity\nurl: https://agentcompany.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher, to use\n    the Services.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Unlawful or rights-infringing uses\n  text: Use the Services to\
  \ develop applications that violate these Terms or applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher, to use\n    the Services.\n"
source_yaml_url: https://artifacts.apis.io/agentuity/eligibility/agentuity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Agentuity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agents
- Artificial Intelligence
- Cloud
- Serverless
- Platform
- Developer Tools
- LLM
- Infrastructure
- Deployment
- AI Gateway
---
