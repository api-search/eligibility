---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of a company or other entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated data without separate agreement
    text: Process protected health information ("PHI") subject to HIPAA, payment card data subject to PCI-DSS, or similarly regulated data without entering into a separate written agreement with 21st Labs Inc. addressing those requirements.
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
name: 21st
provenance_date: '2026-11-09'
provider_name: 21st
provider_slug: 21st
slug: 21st-eligibility
source_date: '2026-11-09'
source_filename: 21st-eligibility.yml
source_heading: Eligibility
source_page: https://21st.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 21st\naid: 21st\nurl: https://21st.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of a company or other entity, you represent that you have authority\n    to bind that entity.\nrestricted_uses:\n- summary: Regulated data without separate agreement\n  text: Process protected health information (\"PHI\") subject to HIPAA, payment card data subject to PCI-DSS, or\n    similarly regulated data without entering into a separate written agreement with 21st Labs Inc. addressing those\n  \
  \  requirements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/21st/eligibility/21st-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from 21st's own page on 2026-11-09.
synthetic: false
tags:
- Company
- UI Components
- React
- MCP
- Developer Tools
- Artificial Intelligence
- Agents
- Design Systems
- Frontend
- Component Registry
---
