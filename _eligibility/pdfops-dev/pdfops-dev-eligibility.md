---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-safety or critical flows
    text: you shouldn't build life-safety or similarly critical flows on it
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Keys are issued per email address and delivered by email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: pdfops-dev
provenance_date: '2026-11-10'
provider_name: pdfops-dev
provider_slug: pdfops-dev
slug: pdfops-dev-eligibility
source_date: '2026-11-10'
source_filename: pdfops-dev-eligibility.yml
source_heading: Eligibility
source_page: https://pdfops.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pdfops-dev\naid: pdfops-dev\nurl: https://pdfops.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Life-safety or critical flows\n  text: you shouldn't build life-safety or similarly critical flows on it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Keys are issued per email address and delivered by email.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pdfops-dev/eligibility/pdfops-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from pdfops-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Artificial Intelligence
- No-Code
- Python
---
