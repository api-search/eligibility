---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged eighteen (18) years or older.
    type: individual
  - text: If you are using the Site on behalf of a company, organization, or other legal entity (collectively, "Company"), you represent and warrant that you have the authority to bind the Company to this Agreement.
    type: business
  minimum_age:
    text: The Site is only intended for individuals aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Malicious, illegal or fraudulent use
    text: use the Site in any manner that is otherwise malicious, illegal or fraudulent
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
name: Baz Technologies
provenance_date: '2026-11-09'
provider_name: Baz Technologies
provider_slug: baz-technologies
slug: baz-technologies-eligibility
source_date: '2026-11-09'
source_filename: baz-technologies-eligibility.yml
source_heading: Eligibility
source_page: https://baz.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baz Technologies\naid: baz-technologies\nurl: https://baz.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\n- type: business\n  text: If you are using the Site on behalf of a company, organization, or other legal entity (collectively, \"Company\"),\n    you represent and warrant that you have the authority to bind the Company to this Agreement.\nrestricted_uses:\n- summary: Malicious, illegal or fraudulent use\n  text: use the Site in any manner that\
  \ is otherwise malicious, illegal or fraudulent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/baz-technologies/eligibility/baz-technologies-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Baz Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Review
- Developer Tools
- AI Agents
- Application Security
- Agentic Coding
- DevOps
- MCP
- Software Engineering
---
