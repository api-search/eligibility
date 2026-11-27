---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Enigma Services are controlled and operated from the United States
  entity_types:
  - text: If you are accessing or using Enigma Services on behalf of an organization, then you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: If you are under the age of 18, you are not permitted to use Enigma Services.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction
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
name: Enigma Analytics
provenance_date: '2026-11-09'
provider_name: Enigma Analytics
provider_slug: enigma-analytics
slug: enigma-analytics-eligibility
source_date: '2026-11-09'
source_filename: enigma-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.enigma.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enigma Analytics\naid: enigma-analytics\nurl: https://www.enigma.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Enigma Services are controlled and operated from the United States\nentity_types:\n- type: business\n  text: If you are accessing or using Enigma Services on behalf of an organization, then you are agreeing to these\n    Terms for that organization\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo\n    or other restriction\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under the age of 18, you are not permitted to use Enigma Services.\n"
source_yaml_url: https://artifacts.apis.io/enigma-analytics/eligibility/enigma-analytics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Enigma Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business Data
- KYB
- Identity Verification
- Compliance
- Sanctions Screening
- GraphQL
- Fintech
- Data Enrichment
- MCP
- Agent Skills
- Payments Risk
---
