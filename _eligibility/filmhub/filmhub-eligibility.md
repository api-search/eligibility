---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Filmhub, the Sites, and the Services are based in the United States. Users who access or use the Sites or Services from outside the United States are responsible for complying with all applicable laws
  entity_types:
  - text: If you open a User Account on behalf of a company, organization, or other entity, then (i) "you" includes that entity
    type: business
  minimum_age:
    text: You must be at least 13 years old to access the Sites and use the Services, and you must be at least 18 years old to upload Your Content via the Services.
    value: '13'
  restricted_uses:
  - summary: Restricted content types
    text: Upload, submit, post, email, or otherwise transmit, via the Sites or Services, any content or other materials that, in the sole opinion of Filmhub, are unlawful, harmful, threatening, obscene, harassing, defamatory or hateful
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
name: Filmhub
provenance_date: '2026-11-09'
provider_name: Filmhub
provider_slug: filmhub
slug: filmhub-eligibility
source_date: '2026-11-09'
source_filename: filmhub-eligibility.yml
source_heading: Eligibility
source_page: https://filmhub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Filmhub\naid: filmhub\nurl: https://filmhub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Filmhub, the Sites, and the Services are based in the United States. Users who access or use the Sites or\n    Services from outside the United States are responsible for complying with all applicable laws\nentity_types:\n- type: business\n  text: If you open a User Account on behalf of a company, organization, or other entity, then (i) \"you\" includes\n    that entity\nrestricted_uses:\n- summary: Restricted content types\n  text: Upload, submit, post, email,\
  \ or otherwise transmit, via the Sites or Services, any content or other materials\n    that, in the sole opinion of Filmhub, are unlawful, harmful, threatening, obscene, harassing, defamatory or\n    hateful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to access the Sites and use the Services, and you must be at least 18\n    years old to upload Your Content via the Services.\n"
source_yaml_url: https://artifacts.apis.io/filmhub/eligibility/filmhub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Filmhub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Film Distribution
- Streaming
- Media and Entertainment
- Video
- Marketplace
- Content Licensing
- FAST
---
