---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our services are not directed to children under 13, and we do not knowingly collect personal data from children.
    value: '13'
  restricted_uses:
  - summary: AI model training on site content
    text: in connection with the development, training, fine-tuning, testing or evaluation of artificial intelligence (AI) or machine learning models
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may need to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WhatFontIS
provenance_date: '2026-11-10'
provider_name: WhatFontIS
provider_slug: whatfontis
slug: whatfontis-eligibility
source_date: '2026-11-10'
source_filename: whatfontis-eligibility.yml
source_heading: Eligibility
source_page: https://whatfontis.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WhatFontIS\naid: whatfontis\nurl: https://whatfontis.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: AI model training on site content\n  text: in connection with the development, training, fine-tuning, testing or evaluation of artificial intelligence\n    (AI) or machine learning models\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may need to verify your identity.\nminimum_age:\n  value: '13'\n  text: Our services are not directed to children under 13, and we do not knowingly collect\
  \ personal data from children.\n"
source_yaml_url: https://artifacts.apis.io/whatfontis/eligibility/whatfontis-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from WhatFontIS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Font Identification
- Artificial Intelligence
- Design Tools
- Typography
---
