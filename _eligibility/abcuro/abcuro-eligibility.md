---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company makes no claims concerning whether the content on this website may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No medical advice reliance
    text: you should not use this information for diagnosing or treating a health problem or disease.
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
name: Abcuro
provenance_date: '2026-11-09'
provider_name: Abcuro
provider_slug: abcuro
slug: abcuro-eligibility
source_date: '2026-11-09'
source_filename: abcuro-eligibility.yml
source_heading: Eligibility
source_page: https://abcuro.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abcuro\naid: abcuro\nurl: https://abcuro.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company makes no claims concerning whether the content on this website may be downloaded, viewed, or\n    be appropriate for use outside of the United States.\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\nrestricted_uses:\n- summary: No medical advice reliance\n  text: you should not use this information for diagnosing or treating a health problem or disease.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/abcuro/eligibility/abcuro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Abcuro's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Pharmaceuticals
- Immunology
- Autoimmune Disease
- Oncology
- Clinical Trials
- Life Sciences
- Drug Development
- Healthcare
- content-api
- WordPress
---
