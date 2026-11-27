---
claim_count: 1
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
  - summary: Not for seeking medical treatment
    text: You represent to us (which representation shall be deemed to be made each time you use the Website) that you are not using the Website for the purpose of seeking medical attention or treatment.
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
name: Geneoscopy
provenance_date: '2026-11-09'
provider_name: Geneoscopy
provider_slug: geneoscopy
slug: geneoscopy-eligibility
source_date: '2026-11-09'
source_filename: geneoscopy-eligibility.yml
source_heading: Eligibility
source_page: https://www.geneoscopy.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geneoscopy\naid: geneoscopy\nurl: https://www.geneoscopy.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for seeking medical treatment\n  text: You represent to us (which representation shall be deemed to be made each time you use the Website) that\n    you are not using the Website for the purpose of seeking medical attention or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/geneoscopy/eligibility/geneoscopy-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Geneoscopy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Diagnostics
- Molecular Diagnostics
- Colorectal Cancer
- Cancer Screening
- RNA
- Clinical Laboratory
- Life Sciences
- Gastroenterology
---
