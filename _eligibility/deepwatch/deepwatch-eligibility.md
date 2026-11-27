---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company or organization (the “ Customer ”) using the Solution
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-critical environments
    text: Customer shall not use Deepwatch Solutions in any environment in which failure could lead to death, personal injury, or any physical or environmental damage.
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
name: Deepwatch
provenance_date: '2026-11-09'
provider_name: Deepwatch
provider_slug: deepwatch
slug: deepwatch-eligibility
source_date: '2026-11-09'
source_filename: deepwatch-eligibility.yml
source_heading: Eligibility
source_page: https://legal.deepwatch.com/tscs-2025-2
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deepwatch\naid: deepwatch\nurl: https://legal.deepwatch.com/tscs-2025-2\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company or organization (the “ Customer ”) using the Solution\nrestricted_uses:\n- summary: Life-critical environments\n  text: Customer shall not use Deepwatch Solutions in any environment in which failure could lead to death, personal\n    injury, or any physical or environmental damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deepwatch/eligibility/deepwatch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Deepwatch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Managed Detection and Response
- Security Operations
- Threat Intelligence
- Vulnerability Management
- Managed Security Services
- AI Agents
---
