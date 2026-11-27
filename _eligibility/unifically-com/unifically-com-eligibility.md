---
api_specs:
- filename: unifically-com-openapi-generated.yml
  format: yaml
  label: unifically-com API
  slug: unifically-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unifically-com/openapi/_ae-authored/unifically-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - KP
    served: []
    text: Our services are not available in North Korea, or in the Abkhazia and Tskhinvali regions of Georgia, because Georgian law and United Nations sanctions prohibit them there.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, and legally capable of entering into a binding contract to use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Generating CSAM or non-consensual intimate content
    text: Generating, distributing, or storing child sexual abuse material (CSAM). This is strictly prohibited and will result in immediate account termination and reporting to authorities
  - summary: Adult content outside NSFW option
    text: Legal adult content is allowed only through a model's NSFW option
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: unifically-com
provenance_date: '2026-11-10'
provider_name: unifically-com
provider_slug: unifically-com
slug: unifically-com-eligibility
source_date: '2026-11-10'
source_filename: unifically-com-eligibility.yml
source_heading: Eligibility
source_page: https://unifically.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: unifically-com\naid: unifically-com\nurl: https://unifically.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - KP\n  text: Our services are not available in North Korea, or in the Abkhazia and Tskhinvali regions of Georgia, because\n    Georgian law and United Nations sanctions prohibit them there.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, and legally capable of entering\n    into a binding contract to use our services.\nrestricted_uses:\n- summary: Generating CSAM or non-consensual intimate content\n\
  \  text: Generating, distributing, or storing child sexual abuse material (CSAM). This is strictly prohibited and\n    will result in immediate account termination and reporting to authorities\n- summary: Adult content outside NSFW option\n  text: Legal adult content is allowed only through a model's NSFW option\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/unifically-com/eligibility/unifically-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from unifically-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Unified
- Generation
---
