---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our Site.
    type: individual
  - text: if you or your organization use Corelayer’s products or services pursuant to a separate written agreement with us (for example, a pilot agreement, order form, or master services agreement), that separate agreement governs your use of those products and services.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our Site.
    value: '18'
  restricted_uses:
  - summary: Unauthorized access and interference
    text: 'You will not violate or attempt to violate the security of the Site or Corelayer''s systems or network security, including, without limitation, by: (i) accessing data not intended for users of the Site or gaining unauthorized access to an account, server or any other computer system'
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
name: Corelayer
provenance_date: '2026-11-09'
provider_name: Corelayer
provider_slug: corelayer
slug: corelayer-eligibility
source_date: '2026-11-09'
source_filename: corelayer-eligibility.yml
source_heading: Eligibility
source_page: https://www.corelayer.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corelayer\naid: corelayer\nurl: https://www.corelayer.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our Site.\n- type: business\n  text: if you or your organization use Corelayer’s products or services pursuant to a separate written agreement\n    with us (for example, a pilot agreement, order form, or master services agreement), that separate agreement\n    governs your use of those products and services.\nrestricted_uses:\n- summary: Unauthorized access and interference\n\
  \  text: 'You will not violate or attempt to violate the security of the Site or Corelayer''s systems or network\n    security, including, without limitation, by: (i) accessing data not intended for users of the Site or gaining\n    unauthorized access to an account, server or any other computer system'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/corelayer/eligibility/corelayer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Corelayer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SRE
- Incident Response
- Observability
- Production Support
- Root Cause Analysis
- Anomaly Detection
- DevOps
- Agent-Native
- MCP
- Fintech
- Incident Management
---
