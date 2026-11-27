---
api_specs:
- filename: zerobounce-validation-api-openapi.yml
  format: yaml
  label: ZeroBounce Validation API
  slug: zerobounce-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerobounce/openapi/zerobounce-validation-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not a resident of a country sanctioned by the Office of Foreign Assets Control, Department of the Treasury ("OFAC")
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unsolicited email or unlawful material
    text: 'Customer will not: (i) knowingly use the ZeroBounce Hosted Service or Provider Technology to send unsolicited email'
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
name: ZeroBounce
provenance_date: '2026-11-10'
provider_name: ZeroBounce
provider_slug: zerobounce
slug: zerobounce-eligibility
source_date: '2026-11-10'
source_filename: zerobounce-eligibility.yml
source_heading: Eligibility
source_page: https://www.zerobounce.net/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZeroBounce\naid: zerobounce\nurl: https://www.zerobounce.net/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not a resident of a country sanctioned by the Office of Foreign Assets Control,\n    Department of the Treasury (\"OFAC\")\nentity_types: []\nrestricted_uses:\n- summary: No unsolicited email or unlawful material\n  text: 'Customer will not: (i) knowingly use the ZeroBounce Hosted Service or Provider Technology to send unsolicited\n    email'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zerobounce/eligibility/zerobounce-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from ZeroBounce's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- Email Deliverability
- Marketing
- Lead Scoring
- Anti-Spam
- Data Quality
- Email Finder
- Deliverability Monitoring
- DMARC
- Email
---
