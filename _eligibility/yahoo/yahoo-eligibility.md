---
api_specs:
- filename: public
  format: yaml
  label: Yahoo DSP Traffic API
  slug: dsp-traffic-api
  spec_type: Postman
  url: https://www.postman.com/yahoodsp/workspace/public
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The individual who accepts these terms and conditions must be aged 13 years or older, must possess his or her own valid Yahoo account
    type: individual
  - text: If you are entering this TOU on behalf of a company or other legal entity, you represent that you have the legal authority to bind the legal entity to this TOU
    type: business
  minimum_age:
    text: The individual who accepts these terms and conditions must be aged 13 years or older
    value: '13'
  restricted_uses:
  - summary: Nuclear, life-support or mission-critical use
    text: Use the Yahoo APIs to operate nuclear facilities, life support, or other mission critical applications where human life or property may be at stake.
  - summary: Services directed to children
    text: Use the Yahoo APIs on or in a website or service directed to children, as defined by the Children’s Online Privacy Protection Act, unless otherwise expressly agreed to in writing by Yahoo.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate identification, contact, and other information required as part of the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yahoo
provenance_date: '2026-11-10'
provider_name: Yahoo
provider_slug: yahoo
slug: yahoo-eligibility
source_date: '2026-11-10'
source_filename: yahoo-eligibility.yml
source_heading: Eligibility
source_page: https://legal.yahoo.com/us/en/yahoo/terms/product-atos/apiforydn/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yahoo\naid: yahoo\nurl: https://legal.yahoo.com/us/en/yahoo/terms/product-atos/apiforydn/index.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The individual who accepts these terms and conditions must be aged 13 years or older, must possess his or\n    her own valid Yahoo account\n- type: business\n  text: If you are entering this TOU on behalf of a company or other legal entity, you represent that you have the\n    legal authority to bind the legal entity to this TOU\nrestricted_uses:\n- summary: Nuclear, life-support or mission-critical\
  \ use\n  text: Use the Yahoo APIs to operate nuclear facilities, life support, or other mission critical applications where\n    human life or property may be at stake.\n- summary: Services directed to children\n  text: Use the Yahoo APIs on or in a website or service directed to children, as defined by the Children’s Online\n    Privacy Protection Act, unless otherwise expressly agreed to in writing by Yahoo.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate identification, contact, and other information required as part of the registration\n    process.\nminimum_age:\n  value: '13'\n  text: The individual who accepts these terms and conditions must be aged 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/yahoo/eligibility/yahoo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Yahoo's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Programmatic Advertising
- DSP
- Fantasy Sports
- Sports Data
- Identity
- OpenID Connect
- OAuth
- Audience Data
- Media
- Reporting
- Conversion Tracking
- Authentication
---
