---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Site, you must be at least 18 years old (or the age of majority in your jurisdiction).
    type: individual
  minimum_age:
    text: To use the Site, you must be at least 18 years old (or the age of majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Investigational product
    text: TRX-248 is investigational and has not been approved by the U.S. Food and Drug Administration or any other regulatory authority.
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
name: Corsair Pharma
provenance_date: '2026-11-09'
provider_name: Corsair Pharma
provider_slug: corsair-pharma
slug: corsair-pharma-eligibility
source_date: '2026-11-09'
source_filename: corsair-pharma-eligibility.yml
source_heading: Eligibility
source_page: https://www.corsairpharma.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corsair Pharma\naid: corsair-pharma\nurl: https://www.corsairpharma.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Site, you must be at least 18 years old (or the age of majority in your jurisdiction).\nrestricted_uses:\n- summary: Investigational product\n  text: TRX-248 is investigational and has not been approved by the U.S. Food and Drug Administration or any other\n    regulatory authority.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: To use the Site, you must be at least 18 years old (or the age of majority in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/corsair-pharma/eligibility/corsair-pharma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Corsair Pharma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmaceuticals
- Biotechnology
- Life Sciences
- Drug Development
- Clinical Trials
- Pulmonary Arterial Hypertension
- Transdermal Delivery
---
