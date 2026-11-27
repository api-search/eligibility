---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Due to your geographic location, the Services or some of its features or content may be unavailable to you.
  entity_types:
  - text: If you do not have the legal capacity in your jurisdiction to accept these Terms, you must ask a parent or legal guardian to read this Agreement and accept it on your behalf.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful content
    text: You must not submit User Content that violates any laws or infringes on anyone’s rights.
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
name: k-ID
provenance_date: '2026-11-09'
provider_name: k-ID
provider_slug: k-id
slug: k-id-eligibility
source_date: '2026-11-09'
source_filename: k-id-eligibility.yml
source_heading: Eligibility
source_page: https://k-id.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: k-ID\naid: k-id\nurl: https://k-id.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Due to your geographic location, the Services or some of its features or content may be unavailable to you.\nentity_types:\n- type: individual\n  text: If you do not have the legal capacity in your jurisdiction to accept these Terms, you must ask a parent\n    or legal guardian to read this Agreement and accept it on your behalf.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: You must not submit User Content that violates any laws or infringes on anyone’s rights.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/k-id/eligibility/k-id-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from k-ID's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Age Verification
- Age Assurance
- Compliance
- Parental Consent
- Child Safety
- Identity
- Privacy
- RegTech
- Gaming
---
