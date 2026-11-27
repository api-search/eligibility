---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the scanner or API, you confirm that the pictured person is 18 or older and that you are authorized to submit the image.
    value: '18'
  restricted_uses:
  - summary: Harassment, impersonation, surveillance
    text: Do not use iLook to harass, shame, impersonate, exploit, surveil, discriminate against, or make high-impact decisions about any person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: API keys may be issued, limited, rotated, or revoked.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: iLook AI Face Analysis (Wallic Technologies)
provenance_date: '2026-11-09'
provider_name: iLook AI Face Analysis (Wallic Technologies)
provider_slug: ilook
slug: ilook-eligibility
source_date: '2026-11-09'
source_filename: ilook-eligibility.yml
source_heading: Eligibility
source_page: https://www.ilook.fit/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iLook AI Face Analysis (Wallic Technologies)\naid: ilook\nurl: https://www.ilook.fit/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment, impersonation, surveillance\n  text: Do not use iLook to harass, shame, impersonate, exploit, surveil, discriminate against, or make high-impact\n    decisions about any person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: API keys may be issued, limited, rotated, or revoked.\nminimum_age:\n  value: '18'\n  text: By using the scanner or API, you confirm\
  \ that the pictured person is 18 or older and that you are authorized\n    to submit the image.\n"
source_yaml_url: https://artifacts.apis.io/ilook/eligibility/ilook-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from iLook AI Face Analysis (Wallic Technologies)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- FaceAnalysis
- Image Processing
---
