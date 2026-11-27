---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use, duplication or disclosure by the government is subject to restrictions as set forth in subparagraph (c)(1)(ii) of the Rights in Technical Data and Computer Software clause
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law violations
    text: You may not access, download, use or export the Information in violation of U.S. export laws or regulations
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
name: Arcserve
provenance_date: '2026-11-09'
provider_name: Arcserve
provider_slug: arcserve
slug: arcserve-eligibility
source_date: '2026-11-09'
source_filename: arcserve-eligibility.yml
source_heading: Eligibility
source_page: https://www.arcserve.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arcserve\naid: arcserve\nurl: https://www.arcserve.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: Use, duplication or disclosure by the government is subject to restrictions as set forth in subparagraph\n    (c)(1)(ii) of the Rights in Technical Data and Computer Software clause\nrestricted_uses:\n- summary: Export law violations\n  text: You may not access, download, use or export the Information in violation of U.S. export laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arcserve/eligibility/arcserve-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Arcserve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Protection
- Backup
- Disaster Recovery
- Business Continuity
- Ransomware
- Immutable Storage
- SaaS Backup
- Data Resilience
---
