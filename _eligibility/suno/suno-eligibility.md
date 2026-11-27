---
api_specs:
- filename: suno-lyrics-api-openapi.yml
  format: yaml
  label: Suno Lyrics API
  slug: suno-lyrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suno/openapi/suno-lyrics-api-openapi.yml
- filename: suno-music-api-openapi.yml
  format: yaml
  label: Suno Music API
  slug: suno-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suno/openapi/suno-music-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not a person who is barred from using the Services under the laws of the United States or any other applicable jurisdiction
  entity_types:
  - text: you are 18 years of age or older and have the legal capacity to enter into these Terms of Service
    type: individual
  - text: If you are using the Services on behalf of a business or some other entity, you represent that you are authorized to bind that business or entity to these Terms
    type: business
  - text: If you are an enterprise user, you must contact sales to use our Service
    type: other
  minimum_age:
    text: You must be at least 13 years old to use the Service. In addition, if you are under 18 years old, you may use the Service only with the express consent of your parent or guardian
    value: '13'
  restricted_uses:
  - summary: Impersonation
    text: impersonate any person or entity
  - summary: Unlawful or harmful use
    text: is (or is used for or in connection with any purpose, initiative, activity, product or service that is) unlawful, harmful, threatening, abusive, harassing, tortious
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
name: Suno
provenance_date: '2026-11-10'
provider_name: Suno
provider_slug: suno
slug: suno-eligibility
source_date: '2026-11-10'
source_filename: suno-eligibility.yml
source_heading: Eligibility
source_page: https://suno.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Suno\naid: suno\nurl: https://suno.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are not a person who is barred from using the Services under the laws of the United States or any other\n    applicable jurisdiction\nentity_types:\n- type: individual\n  text: you are 18 years of age or older and have the legal capacity to enter into these Terms of Service\n- type: business\n  text: If you are using the Services on behalf of a business or some other entity, you represent that you are authorized\n    to bind that business or entity to these Terms\n\
  - type: other\n  text: If you are an enterprise user, you must contact sales to use our Service\nrestricted_uses:\n- summary: Impersonation\n  text: impersonate any person or entity\n- summary: Unlawful or harmful use\n  text: is (or is used for or in connection with any purpose, initiative, activity, product or service that is)\n    unlawful, harmful, threatening, abusive, harassing, tortious\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service. In addition, if you are under 18 years old, you may\n    use the Service only with the express consent of your parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/suno/eligibility/suno-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Suno's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Music Generation
- Audio
- Generative
- Text-to-Speech
- Music
---
