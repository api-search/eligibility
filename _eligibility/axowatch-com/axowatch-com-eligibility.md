---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: These terms are the agreement between you and Sybrik Development, a business in Ontario, Canada
  entity_types:
  - text: AxoWatch is a tool for businesses.
    type: business
  minimum_age:
    text: You must be at least 18 to use it.
    value: '18'
  restricted_uses:
  - summary: Monitoring without permission
    text: monitor, test or load sites you are not allowed to
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
name: AxoWatch
provenance_date: '2026-11-09'
provider_name: AxoWatch
provider_slug: axowatch-com
slug: axowatch-com-eligibility
source_date: '2026-11-09'
source_filename: axowatch-com-eligibility.yml
source_heading: Eligibility
source_page: https://axowatch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AxoWatch\naid: axowatch-com\nurl: https://axowatch.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: These terms are the agreement between you and Sybrik Development, a business in Ontario, Canada\nentity_types:\n- type: business\n  text: AxoWatch is a tool for businesses.\nrestricted_uses:\n- summary: Monitoring without permission\n  text: monitor, test or load sites you are not allowed to\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to use it.\n"
source_yaml_url: https://artifacts.apis.io/axowatch-com/eligibility/axowatch-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AxoWatch's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Uptime
- Performance
- Error Tracking
- Artificial Intelligence
- Software-as-a-Service
---
