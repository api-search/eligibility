---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Geoblocking may apply to specific geographic regions or countries, but no countries are named.
  entity_types:
  - text: These Terms apply to individual users, team plan customers, and enterprise plan customers
    type: individual
  - text: If you're agreeing to the Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity's behalf
    type: business
  minimum_age:
    text: You must be at least 18 years old or the minimum age required in your country to consent to use the Services.
    value: '18'
  restricted_uses:
  - summary: Inappropriate content
    text: 'Explicit Material : Content that includes nudity, sexual acts, or explicit imagery.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to register for an account (an "Account") to access some or all of our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Genspark
provenance_date: '2026-11-09'
provider_name: Genspark
provider_slug: genspark
slug: genspark-eligibility
source_date: '2026-11-09'
source_filename: genspark-eligibility.yml
source_heading: Eligibility
source_page: https://www.genspark.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Genspark\naid: genspark\nurl: https://www.genspark.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Geoblocking may apply to specific geographic regions or countries, but no countries are named.\nentity_types:\n- type: individual\n  text: These Terms apply to individual users, team plan customers, and enterprise plan customers\n- type: business\n  text: If you're agreeing to the Terms on behalf of an organization or entity, you represent and warrant that you\n    are authorized to agree to these Terms on that organization or entity's behalf\nrestricted_uses:\n- summary: Inappropriate\
  \ content\n  text: 'Explicit Material : Content that includes nudity, sexual acts, or explicit imagery.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to register for an account (an \"Account\") to access some or all of our Services.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the minimum age required in your country to consent to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/genspark/eligibility/genspark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Genspark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- MCP
- Productivity
- Automation
- Search
- Workspace
- A2A
---
