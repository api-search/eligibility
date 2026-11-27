---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: APIDNA which publishes and owns APIDNA platform is a US company registered in the state of Delaware, US.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing material
    text: use the Service to store or transmit infringing, libelous, or otherwise unlawful or tortious material, or to store or transmit material in violation of third-party privacy rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access the Service, Providers and Users must register with APIDNA by completing the registration forms provided via the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: APIDNA
provenance_date: '2026-11-09'
provider_name: APIDNA
provider_slug: apidna
slug: apidna-eligibility
source_date: '2026-11-09'
source_filename: apidna-eligibility.yml
source_heading: Eligibility
source_page: https://apidna.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIDNA\naid: apidna\nurl: https://apidna.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: APIDNA which publishes and owns APIDNA platform is a US company registered in the state of Delaware, US.\nrestricted_uses:\n- summary: Unlawful or infringing material\n  text: use the Service to store or transmit infringing, libelous, or otherwise unlawful or tortious material, or\n    to store or transmit material in violation of third-party privacy rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: In order to access the Service, Providers and Users must register with APIDNA by completing the registration\n    forms provided via the Site.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apidna/eligibility/apidna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from APIDNA's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Enterprise
- Agents
- Integration
---
