---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, and will not use the services from, a country or region subject to comprehensive sanctions
  entity_types:
  - text: If you are using the services on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sexual content involving real people
    text: Generate sexual content involving real people without consent, or any sexual content involving minors.
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
provider_slug: palettelabs-com
slug: palettelabs-com-eligibility
source_date: '2026-11-10'
source_filename: palettelabs-com-eligibility.yml
source_heading: Eligibility
source_page: https://palettelabs.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Palette 2\naid: palettelabs-com\nurl: https://palettelabs.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, and will not use the services from, a country or region subject\n    to comprehensive sanctions\nentity_types:\n- type: business\n  text: If you are using the services on behalf of an organization, you represent that you have authority to bind\n    that organization\nrestricted_uses:\n- summary: Sexual content involving real people\n  text: Generate sexual content involving real people without consent, or any sexual\
  \ content involving minors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/palettelabs-com/eligibility/palettelabs-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Palette 2's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Media
- Content Creation
- Platform
---
