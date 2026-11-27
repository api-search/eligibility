---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms on behalf of a company or other legal entity, you represent that you have authority to bind that entity, and “you” refers to that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Sites or the Service.
    value: '18'
  restricted_uses:
  - summary: High risk activities
    text: use the Service for High Risk Activities
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
name: MindsDB
provenance_date: '2026-11-10'
provider_name: MindsDB
provider_slug: mindsdb
slug: mindsdb-eligibility
source_date: '2026-11-10'
source_filename: mindsdb-eligibility.yml
source_heading: Eligibility
source_page: https://mindshub.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MindsDB\naid: mindsdb\nurl: https://mindshub.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity, and “you” refers to that entity.\nrestricted_uses:\n- summary: High risk activities\n  text: use the Service for High Risk Activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the\
  \ Sites or the Service.\n"
source_yaml_url: https://artifacts.apis.io/mindsdb/eligibility/mindsdb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MindsDB's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- AI Agents
- Data
- Database
- SQL
- Knowledge Base
- MCP
- Open Source
---
