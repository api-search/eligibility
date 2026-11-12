---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is licensed for corporate and organizational use only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Corporate/organizational use only
    text: The service is licensed for corporate and organizational use only.
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
name: CounselAudit
provenance_date: '2026-11-09'
provider_name: CounselAudit
provider_slug: counselaudit-com
slug: counselaudit-com-eligibility
source_date: '2026-11-09'
source_filename: counselaudit-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.counselaudit.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CounselAudit\naid: counselaudit-com\nurl: https://www.counselaudit.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is licensed for corporate and organizational use only.\nrestricted_uses:\n- summary: Corporate/organizational use only\n  text: The service is licensed for corporate and organizational use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/counselaudit-com/eligibility/counselaudit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CounselAudit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Technology
- Legal Billing
- Invoice Review
- Legal Spend Management
- Outside Counsel Guidelines
- Artificial Intelligence
- MCP
---
