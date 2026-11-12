---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter into a binding contract.
    type: individual
  - text: If you act on behalf of an organisation, you confirm that you have authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may restrict account access until your email address has been verified.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Complyzard
provenance_date: '2026-11-09'
provider_name: Complyzard
provider_slug: complyzard-com
slug: complyzard-com-eligibility
source_date: '2026-11-09'
source_filename: complyzard-com-eligibility.yml
source_heading: Eligibility
source_page: https://complyzard.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Complyzard\naid: complyzard-com\nurl: https://complyzard.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter into a binding contract.\n- type: business\n  text: If you act on behalf of an organisation, you confirm that you have authority to bind that organisation to\n    these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may restrict account access until your email address has been verified.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/complyzard-com/eligibility/complyzard-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Complyzard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Governance Risk and Compliance
- Information Security
- Privacy
- AI Governance
- Document Marketplace
- Model Context Protocol
---
