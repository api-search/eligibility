---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Content on our Site is appropriate, legal or available for use in other locations.
  entity_types:
  - text: You will access and use the Site solely for your personal purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You expressly agree not to export or re-export any of the Content to countries or persons prohibited under the export control laws of the United States.
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
name: Komodo Health
provenance_date: '2026-11-09'
provider_name: Komodo Health
provider_slug: komodo-health
slug: komodo-health-eligibility
source_date: '2026-11-09'
source_filename: komodo-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.komodohealth.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Komodo Health\naid: komodo-health\nurl: https://www.komodohealth.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Content on our Site is appropriate, legal or available for use in other\n    locations.\nentity_types:\n- type: individual\n  text: You will access and use the Site solely for your personal purposes.\nrestricted_uses:\n- summary: Export restrictions\n  text: You expressly agree not to export or re-export any of the Content to countries or persons prohibited under\n    the export control laws of the United States.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/komodo-health/eligibility/komodo-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Komodo Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- Life Sciences
- Real-World Data
- Healthcare Analytics
- Artificial Intelligence
- Data
- Snowflake
- MCP
---
