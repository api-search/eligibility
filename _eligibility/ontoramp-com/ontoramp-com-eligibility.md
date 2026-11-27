---
api_specs:
- filename: ontoramp-com-commerce-api-openapi.yml
  format: yaml
  label: ontoramp-com Commerce API
  slug: ontoramp-com-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-commerce-api-openapi.yml
- filename: ontoramp-com-decision-intelligence-api-openapi.yml
  format: yaml
  label: ontoramp-com Decision Intelligence API
  slug: ontoramp-com-decision-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-decision-intelligence-api-openapi.yml
- filename: ontoramp-com-governance-evaluator-api-openapi.yml
  format: yaml
  label: ontoramp-com Governance Evaluator API
  slug: ontoramp-com-governance-evaluator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-governance-evaluator-api-openapi.yml
- filename: ontoramp-com-knowledge-graph-api-openapi.yml
  format: yaml
  label: ontoramp-com Knowledge Graph API
  slug: ontoramp-com-knowledge-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-knowledge-graph-api-openapi.yml
- filename: ontoramp-com-projection-engine-api-openapi.yml
  format: yaml
  label: ontoramp-com Projection Engine API
  slug: ontoramp-com-projection-engine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-projection-engine-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an Account.
    type: individual
  - text: If you are accepting these Terms on behalf of an organization, you represent that you have authority to bind that organization, and " you " or " Customer " means that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an Account.
    value: '18'
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
name: ontoramp-com
provenance_date: '2026-11-10'
provider_name: ontoramp-com
provider_slug: ontoramp-com
slug: ontoramp-com-eligibility
source_date: '2026-11-10'
source_filename: ontoramp-com-eligibility.yml
source_heading: Eligibility
source_page: https://ontoramp.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ontoramp-com\naid: ontoramp-com\nurl: https://ontoramp.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an Account.\n- type: business\n  text: If you are accepting these Terms on behalf of an organization, you represent that you have authority to\n    bind that organization, and \" you \" or \" Customer \" means that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to create an Account.\n"
source_yaml_url: https://artifacts.apis.io/ontoramp-com/eligibility/ontoramp-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from ontoramp-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- AI Agents
- Compliance
- Certification
---
