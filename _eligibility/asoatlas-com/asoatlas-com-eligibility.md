---
api_specs:
- filename: asoatlas-com-openapi-generated.yml
  format: yaml
  label: ASO Atlas API
  slug: asoatlas-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoatlas-com/openapi/_ae-authored/asoatlas-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: References to "you" mean the person or organisation using the Service.
    type: other
  minimum_age:
    text: You must be at least 18 years old, or old enough to enter a binding contract where you live.
    value: '18'
  restricted_uses:
  - summary: No unlawful use
    text: use the Service to break the law, infringe someone's rights, or violate Apple's terms for the App Store or App Store Connect
  - summary: No analytics in child-directed apps without compliance
    text: Do not use analytics in an app directed at children (the App Store Kids category, or an app in Google Play's Families program) unless you comply with those programs' rules and the law that applies to you
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
name: ASO Atlas
provenance_date: '2026-11-09'
provider_name: ASO Atlas
provider_slug: asoatlas-com
slug: asoatlas-com-eligibility
source_date: '2026-11-09'
source_filename: asoatlas-com-eligibility.yml
source_heading: Eligibility
source_page: https://asoatlas.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ASO Atlas\naid: asoatlas-com\nurl: https://asoatlas.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: References to \"you\" mean the person or organisation using the Service.\nrestricted_uses:\n- summary: No unlawful use\n  text: use the Service to break the law, infringe someone's rights, or violate Apple's terms for the App Store\n    or App Store Connect\n- summary: No analytics in child-directed apps without compliance\n  text: Do not use analytics in an app directed at children (the App Store Kids category, or an app in Google\
  \ Play's\n    Families program) unless you comply with those programs' rules and the law that applies to you\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or old enough to enter a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/asoatlas-com/eligibility/asoatlas-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ASO Atlas's own page on 2026-11-09.
synthetic: false
tags:
- ASO
- App Store
- Keyword Research
- Analytics
- Software-as-a-Service
---
