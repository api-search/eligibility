---
api_specs:
- filename: seinetwork-io-openapi-generated.yml
  format: yaml
  label: Sei API
  slug: seinetwork-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seinetwork-io/openapi/_ae-authored/seinetwork-io-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services access the Site in the jurisdictions prohibited by applicable law.
  entity_types:
  - text: By accessing or using the Services, you agree that you have reached the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: You may not use the Services if you are below the age of majority in your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: Sanctioned persons and entities
    text: The Services also may not be used by or for the specific benefit of (i) any individual or entity on the Specially Designated Nationals and Blocked Persons ("SDN") List maintained by OFAC
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
name: Sei
provenance_date: '2026-11-10'
provider_name: Sei
provider_slug: seinetwork-io
slug: seinetwork-io-eligibility
source_date: '2026-11-10'
source_filename: seinetwork-io-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.sei.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sei\naid: seinetwork-io\nurl: https://dashboard.sei.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services access the Site in the jurisdictions prohibited by applicable law.\nentity_types:\n- type: individual\n  text: By accessing or using the Services, you agree that you have reached the age of majority in your jurisdiction\nrestricted_uses:\n- summary: Sanctioned persons and entities\n  text: The Services also may not be used by or for the specific benefit of (i) any individual or entity on the\n    Specially Designated Nationals and Blocked Persons\
  \ (\"SDN\") List maintained by OFAC\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You may not use the Services if you are below the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/seinetwork-io/eligibility/seinetwork-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sei's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blockchain
- Infrastructure
- Finance
- DeFi
---
