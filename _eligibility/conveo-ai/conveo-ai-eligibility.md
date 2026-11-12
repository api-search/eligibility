---
api_specs:
- filename: conveo-ai-interviews-api-openapi.yml
  format: yaml
  label: Conveo Interviews API
  slug: conveo-ai-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conveo-ai/openapi/conveo-ai-interviews-api-openapi.yml
- filename: conveo-ai-studies-api-openapi.yml
  format: yaml
  label: Conveo Studies API
  slug: conveo-ai-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conveo-ai/openapi/conveo-ai-studies-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer means any natural person or legal entity (company, organization, or individual acting as a representative) that has entered into an agreement with Conveo for the use of the Service
    type: business
  minimum_age:
    text: The Service is intended for individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Special category or sensitive data
    text: Input or upload any special categories of personal data (as defined in Article 9 of the GDPR) or other sensitive data (such as health, biometric, or financial-account data) unless explicitly permitted in writing and governed by a Data Processing Addendum signed by both you and Conveo.
  - summary: Automated decisions without human review
    text: Use the Service in connection with automated decision-making that has legal or similarly significant effects on individuals without appropriate human review.
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
name: Conveo
provenance_date: '2026-11-09'
provider_name: Conveo
provider_slug: conveo-ai
slug: conveo-ai-eligibility
source_date: '2026-11-09'
source_filename: conveo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://conveo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conveo\naid: conveo-ai\nurl: https://conveo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer means any natural person or legal entity (company, organization, or individual acting as a representative)\n    that has entered into an agreement with Conveo for the use of the Service\nrestricted_uses:\n- summary: Special category or sensitive data\n  text: Input or upload any special categories of personal data (as defined in Article 9 of the GDPR) or other sensitive\n    data (such as health, biometric, or financial-account\
  \ data) unless explicitly permitted in writing and governed\n    by a Data Processing Addendum signed by both you and Conveo.\n- summary: Automated decisions without human review\n  text: Use the Service in connection with automated decision-making that has legal or similarly significant effects\n    on individuals without appropriate human review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/conveo-ai/eligibility/conveo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Conveo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Qualitative Research
- Market Research
- Customer Interviews
- Consumer Insights
- MCP
---
