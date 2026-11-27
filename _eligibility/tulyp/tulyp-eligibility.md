---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violation of laws or fraud
    text: Violate any applicable laws or regulations
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
name: Tulyp
provenance_date: '2026-11-10'
provider_name: Tulyp
provider_slug: tulyp
slug: tulyp-eligibility
source_date: '2026-11-10'
source_filename: tulyp-eligibility.yml
source_heading: Eligibility
source_page: https://tulyp.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tulyp\naid: tulyp\nurl: https://tulyp.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company or other legal entity, you represent that you have\n    the authority to bind such entity to these Terms.\nrestricted_uses:\n- summary: Violation of laws or fraud\n  text: Violate any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tulyp/eligibility/tulyp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tulyp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Treasury
- Foreign Exchange
- Risk Management
- Software-as-a-Service
- France
---
