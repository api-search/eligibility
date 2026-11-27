---
api_specs:
- filename: openapi.yml
  format: yaml
  label: iHeartRadio Catalog API
  slug: iheartradio-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iheart-radio/openapi.yml
- filename: openapi.yml
  format: yaml
  label: iHeartRadio Live Stations API
  slug: iheartradio-live-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iheart-radio/openapi.yml
- filename: openapi.yml
  format: yaml
  label: iHeartRadio Podcasts API
  slug: iheartradio-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iheart-radio/openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Sites are intended only for individuals or businesses in the United States.
  entity_types:
  - text: 'If you are entering into these Terms for your personal, non-business use of the Site, you represent that: (a) you are a legal resident of the United States'
    type: individual
  - text: If you are entering into these Terms on behalf of a company, business, or other legal entity, by using the Sites you represent that
    type: business
  minimum_age:
    text: if you are not, that you are 13 years or older and have obtained parental or guardian consent to enter into these Terms
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: YOU MAY NOT USE ANY IHEART SITE FOR ANY PURPOSE THAT IS UNLAWFUL OR PROHIBITED BY THESE TERMS, AND/OR ANY ADDITIONAL TERMS.
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
name: iHeartRadio
provenance_date: '2026-11-09'
provider_name: iHeartRadio
provider_slug: iheart-radio
slug: iheart-radio-eligibility
source_date: '2026-11-09'
source_filename: iheart-radio-eligibility.yml
source_heading: Eligibility
source_page: https://www.iheart.com/content/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iHeartRadio\naid: iheart-radio\nurl: https://www.iheart.com/content/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Sites are intended only for individuals or businesses in the United States.\nentity_types:\n- type: individual\n  text: 'If you are entering into these Terms for your personal, non-business use of the Site, you represent that:\n    (a) you are a legal resident of the United States'\n- type: business\n  text: If you are entering into these Terms on behalf of a company, business, or other legal entity, by using the\n    Sites you represent that\n\
  restricted_uses:\n- summary: Unlawful or prohibited use\n  text: YOU MAY NOT USE ANY IHEART SITE FOR ANY PURPOSE THAT IS UNLAWFUL OR PROHIBITED BY THESE TERMS, AND/OR ANY\n    ADDITIONAL TERMS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: if you are not, that you are 13 years or older and have obtained parental or guardian consent to enter into\n    these Terms\n"
source_yaml_url: https://artifacts.apis.io/iheart-radio/eligibility/iheart-radio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from iHeartRadio's own page on 2026-11-09.
synthetic: false
tags:
- Radio
- Podcasts
- Music
- Streaming
- Audio
- Live Radio
- Digital Media
---
