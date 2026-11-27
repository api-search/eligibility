---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a jurisdiction subject to a comprehensive U.S. embargo and that you are not on any U.S. government restricted party list.
  entity_types:
  - text: You must be at least 18 years old and have the legal capacity to form a binding contract.
    type: individual
  - text: If you are accepting these Terms on behalf of an organization, you represent and warrant that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Deceptive or misleading content
    text: Generate content intended to deceive, defraud, or mislead consumers, including fake reviews, misleading advertising, or phishing materials
  - summary: Unsolicited commercial communications
    text: Use the Services to send unsolicited commercial communications (spam), or to facilitate any unlawful activity
  - summary: Sensitive data submission
    text: You agree not to upload or submit protected health information under HIPAA, government identification numbers, payment card numbers, or other categories of sensitive personal data to the Services
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
name: Mutiny
provenance_date: '2026-11-10'
provider_name: Mutiny
provider_slug: mutiny
slug: mutiny-eligibility
source_date: '2026-11-10'
source_filename: mutiny-eligibility.yml
source_heading: Eligibility
source_page: https://www.mutinyhq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mutiny\naid: mutiny\nurl: https://www.mutinyhq.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a jurisdiction subject to a comprehensive U.S. embargo\n    and that you are not on any U.S. government restricted party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal capacity to form a binding contract.\n- type: business\n  text: If you are accepting these Terms on behalf of an organization, you represent and warrant that you have authority\n    to bind that organization.\n\
  restricted_uses:\n- summary: Deceptive or misleading content\n  text: Generate content intended to deceive, defraud, or mislead consumers, including fake reviews, misleading\n    advertising, or phishing materials\n- summary: Unsolicited commercial communications\n  text: Use the Services to send unsolicited commercial communications (spam), or to facilitate any unlawful activity\n- summary: Sensitive data submission\n  text: You agree not to upload or submit protected health information under HIPAA, government identification numbers,\n    payment card numbers, or other categories of sensitive personal data to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal capacity to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/mutiny/eligibility/mutiny-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Mutiny's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Sales
- Marketing
- Go-To-Market
- Artificial Intelligence
- AI Agents
- Sales Enablement
- Account Based Marketing
- Workflow Automation
- MCP
---
