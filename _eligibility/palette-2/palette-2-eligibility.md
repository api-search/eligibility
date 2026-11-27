---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, and will not use the services from, a country or region subject to comprehensive sanctions, and that you are not a person with whom dealings are prohibited under those laws.
  entity_types:
  - text: If you are using the services on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sexual content
    text: Generate sexual content involving real people without consent, or any sexual content involving minors.
  - summary: Real person likeness
    text: Generate material depicting a real person's face, voice, or likeness without their permission, or in a way that is intended to deceive as to its authenticity.
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
name: Palette 2
provenance_date: '2026-11-10'
provider_name: Palette 2
provider_slug: palette-2
slug: palette-2-eligibility
source_date: '2026-11-10'
source_filename: palette-2-eligibility.yml
source_heading: Eligibility
source_page: https://palettelabs.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Palette 2\naid: palette-2\nurl: https://palettelabs.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, and will not use the services from, a country or region subject\n    to comprehensive sanctions, and that you are not a person with whom dealings are prohibited under those laws.\nentity_types:\n- type: business\n  text: If you are using the services on behalf of an organization, you represent that you have authority to bind\n    that organization, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: Sexual content\n\
  \  text: Generate sexual content involving real people without consent, or any sexual content involving minors.\n- summary: Real person likeness\n  text: Generate material depicting a real person's face, voice, or likeness without their permission, or in a way\n    that is intended to deceive as to its authenticity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/palette-2/eligibility/palette-2-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Palette 2's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Video Generation
- Media
- Content Generation
- Multi-Modal
- Creative Tools
---
