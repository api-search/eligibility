---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is intended to be accessed from, and the information contained in the Website is intended to be used within the United States of America.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice or diagnosis
    text: We do not offer medical diagnosis or treatment from this Website, and none of the information contained on this Website should be construed as providing medical advice or services of any kind.
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
name: Flare Therapeutics
provenance_date: '2026-11-09'
provider_name: Flare Therapeutics
provider_slug: flare-therapeutics
slug: flare-therapeutics-eligibility
source_date: '2026-11-09'
source_filename: flare-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://www.flaretx.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flare Therapeutics\naid: flare-therapeutics\nurl: https://www.flaretx.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is intended to be accessed from, and the information contained in the Website is intended to\n    be used within the United States of America.\nentity_types: []\nrestricted_uses:\n- summary: No medical advice or diagnosis\n  text: We do not offer medical diagnosis or treatment from this Website, and none of the information contained\n    on this Website should be construed as providing medical advice or services of any kind.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flare-therapeutics/eligibility/flare-therapeutics-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Flare Therapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Oncology
- Precision Medicine
- transcription-factors
- Drug Discovery
- Clinical Trials
- Life Sciences
- content-api
---
