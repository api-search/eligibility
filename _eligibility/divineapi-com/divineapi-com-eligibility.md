---
api_specs:
- filename: divineapi-com-openapi.yml
  format: yaml
  label: DivineAPI
  slug: divineapi
  spec_type: OpenAPI
  url: https://artifacts.apis.io/divineapi-com/openapi/divineapi-com-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Being at least 18 years of age, or the age of majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Use the Service to generate content that is unlawful, defamatory, fraudulent, hateful, discriminatory, or that infringes third-party rights
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
name: divineapi-com
provenance_date: '2026-11-09'
provider_name: divineapi-com
provider_slug: divineapi-com
slug: divineapi-com-eligibility
source_date: '2026-11-09'
source_filename: divineapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://divineapi.com/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: divineapi-com\naid: divineapi-com\nurl: https://divineapi.com/terms-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Use the Service to generate content that is unlawful, defamatory, fraudulent, hateful, discriminatory, or\n    that infringes third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Being at least 18 years of age, or the age of majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/divineapi-com/eligibility/divineapi-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from divineapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Data
- Developers
- Platform
---
