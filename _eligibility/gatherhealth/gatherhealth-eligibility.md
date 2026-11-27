---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to the Services is intended only for users located within the United States.
  entity_types:
  - text: By using the Services, you represent and warrant that you are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: By using the Services, you represent and warrant that you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: transmit or submit harmful, threatening, abusive, harassing, defamatory, deceptive, fraudulent, obscene, indecent, vulgar, lewd, violent, hateful, or otherwise objectionable content or material;
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
name: Gatherhealth
provenance_date: '2026-11-09'
provider_name: Gatherhealth
provider_slug: gatherhealth
slug: gatherhealth-eligibility
source_date: '2026-11-09'
source_filename: gatherhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.gatherhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gatherhealth\naid: gatherhealth\nurl: https://www.gatherhealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to the Services is intended only for users located within the United States.\nentity_types:\n- type: individual\n  text: By using the Services, you represent and warrant that you are eighteen (18) years of age or older.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: transmit or submit harmful, threatening, abusive, harassing, defamatory, deceptive, fraudulent, obscene,\n    indecent, vulgar, lewd, violent, hateful, or\
  \ otherwise objectionable content or material;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Services, you represent and warrant that you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/gatherhealth/eligibility/gatherhealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gatherhealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Senior Care
- Medicare
- Value-Based Care
- Health Services
---
