---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: '7. US Use Only: This website and its contents are intended to comply with the laws and regulations in the U.S. Although the information on this website is accessible to users outside of the U.S., the information pertaining to treatment and products is intended for use only by residents of the U.S.'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Medical reliance
    text: You should not rely on this website or any other service offered by or through this website for medical diagnosis or treatment.
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
name: Veradermics
provenance_date: '2026-11-10'
provider_name: Veradermics
provider_slug: veradermics
slug: veradermics-eligibility
source_date: '2026-11-10'
source_filename: veradermics-eligibility.yml
source_heading: Eligibility
source_page: https://www.veradermics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Veradermics\naid: veradermics\nurl: https://www.veradermics.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: '7. US Use Only: This website and its contents are intended to comply with the laws and regulations in the\n    U.S. Although the information on this website is accessible to users outside of the U.S., the information pertaining\n    to treatment and products is intended for use only by residents of the U.S.'\nentity_types: []\nrestricted_uses:\n- summary: Medical reliance\n  text: You should not rely on this website or any other service offered by or\
  \ through this website for medical\n    diagnosis or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/veradermics/eligibility/veradermics-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Veradermics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Life Sciences
- Healthcare
- Dermatology
- Clinical Trials
- Drug Development
---
