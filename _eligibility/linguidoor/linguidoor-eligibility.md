---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'User: Individual(s) or a company submitting a Translation Request.'
    type: individual
  - text: 'User: Individual(s) or a company submitting a Translation Request.'
    type: business
  minimum_age:
    text: null
    value: null
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
name: Linguidoor
provenance_date: '2026-11-09'
provider_name: Linguidoor
provider_slug: linguidoor
slug: linguidoor-eligibility
source_date: '2026-11-09'
source_filename: linguidoor-eligibility.yml
source_heading: Eligibility
source_page: https://linguidoor.com/terms-and-conditions-linguidoor-translation-services/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Linguidoor\naid: linguidoor\nurl: https://linguidoor.com/terms-and-conditions-linguidoor-translation-services/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'User: Individual(s) or a company submitting a Translation Request.'\n- type: business\n  text: 'User: Individual(s) or a company submitting a Translation Request.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/linguidoor/eligibility/linguidoor-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Linguidoor's own page on 2026-11-09.
synthetic: false
tags:
- Translation Services
- Localization
- Language Services
- Interpretation
- Document Translation
- Certified Translation
- Content Services
- Media / Dubbing
- Transcription
- AI Data Services
- Professional Services
- Germany
---
