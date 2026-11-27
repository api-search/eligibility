---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are not offered in, and may not be accessed from, Restricted Territories.
  entity_types:
  - text: You must be at least eighteen (18) years of age to create an account and use the Services.
    type: individual
  - text: Use of the Services on behalf of a business, organization, or other entity is not permitted under these Terms unless Privado has agreed to separate terms governing such use.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age to create an account and use the Services.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export control violations
    text: facilitate violations of applicable export control or sanctions laws
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
name: Privado
provenance_date: '2026-11-10'
provider_name: Privado
provider_slug: privadovpn-com
slug: privadovpn-com-eligibility
source_date: '2026-11-10'
source_filename: privadovpn-com-eligibility.yml
source_heading: Eligibility
source_page: https://privadovpn.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Privado\naid: privadovpn-com\nurl: https://privadovpn.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are not offered in, and may not be accessed from, Restricted Territories.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age to create an account and use the Services.\n- type: business\n  text: Use of the Services on behalf of a business, organization, or other entity is not permitted under these\n    Terms unless Privado has agreed to separate terms governing such use.\nrestricted_uses:\n- summary: Sanctions\
  \ and export control violations\n  text: facilitate violations of applicable export control or sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to create an account and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/privadovpn-com/eligibility/privadovpn-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Privado's own page on 2026-11-10.
synthetic: false
tags:
- VPN
- Security
- Privacy
- Antivirus
- Ad Blocking
---
