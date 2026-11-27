---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Tapstitch from its facilities in the United States of America.
  entity_types:
  - text: represent you are of legal age in your jurisdiction of residence to form a binding contract
    type: individual
  - text: on behalf of any company, organization or other legal entity on whose behalf you use the Services
    type: business
  minimum_age:
    text: represent you are of legal age in your jurisdiction of residence to form a binding contract
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: the Services may not be exported or re-exported (a) into any United States embargoed countries
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
name: Tapstitch
provenance_date: '2026-11-10'
provider_name: Tapstitch
provider_slug: tapstitch
slug: tapstitch-eligibility
source_date: '2026-11-10'
source_filename: tapstitch-eligibility.yml
source_heading: Eligibility
source_page: https://www.tapstitch.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tapstitch\naid: tapstitch\nurl: https://www.tapstitch.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Tapstitch from its facilities in the United States of America.\nentity_types:\n- type: individual\n  text: represent you are of legal age in your jurisdiction of residence to form a binding contract\n- type: business\n  text: on behalf of any company, organization or other legal entity on whose behalf you use the Services\nrestricted_uses:\n- summary: Export control restrictions\n  text: the Services may not be exported\
  \ or re-exported (a) into any United States embargoed countries\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: represent you are of legal age in your jurisdiction of residence to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/tapstitch/eligibility/tapstitch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tapstitch's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Print on Demand
- Apparel
- Dropshipping
- E-Commerce
- Fashion
- Fulfillment
---
