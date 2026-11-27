---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are 18 years of age or older and are fully able and competent to enter into the terms
    type: individual
  minimum_age:
    text: The Service is intended for adults 18 years of age or older who may be eligible to participate in clinical trials.
    value: '18'
  restricted_uses:
  - summary: Impersonation and false information
    text: impersonate or misrepresent any person or entity or your affiliation with someone else
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
name: DiscGenics
provenance_date: '2026-11-09'
provider_name: DiscGenics
provider_slug: discgenics
slug: discgenics-eligibility
source_date: '2026-11-09'
source_filename: discgenics-eligibility.yml
source_heading: Eligibility
source_page: https://www.discgenics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DiscGenics\naid: discgenics\nurl: https://www.discgenics.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are 18 years of age or older and are fully able and competent to enter into the terms\nrestricted_uses:\n- summary: Impersonation and false information\n  text: impersonate or misrepresent any person or entity or your affiliation with someone else\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for\
  \ adults 18 years of age or older who may be eligible to participate in clinical\n    trials.\n"
source_yaml_url: https://artifacts.apis.io/discgenics/eligibility/discgenics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DiscGenics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Biopharmaceutical
- Regenerative Medicine
- Cell Therapy
- Healthcare
- Life Sciences
- Clinical Trials
- Spine
- Utah
---
