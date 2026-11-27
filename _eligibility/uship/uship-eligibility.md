---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are registering as a business entity, you represent that You have the authority to bind the entity to this agreement.
    type: business
  - text: You acknowledge that You are at least 18 years of age and you have reached the age of majority in the state or jurisdiction where You live or reside.
    type: individual
  minimum_age:
    text: You acknowledge that You are at least 18 years of age and you have reached the age of majority in the state or jurisdiction where You live or reside.
    value: '18'
  restricted_uses:
  - summary: Transportation services only
    text: You agree that the uShip Services are for transportation services only and that work that You provide will only involve transportation services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Any identity verification methods we employ are strictly on a best efforts basis and should not be solely relied upon by our users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: uShip
provenance_date: '2026-11-10'
provider_name: uShip
provider_slug: uship
slug: uship-eligibility
source_date: '2026-11-10'
source_filename: uship-eligibility.yml
source_heading: Eligibility
source_page: https://help.uship.com/hc/en-us/articles/360008771433-User-Agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: uShip\naid: uship\nurl: https://help.uship.com/hc/en-us/articles/360008771433-User-Agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are registering as a business entity, you represent that You have the authority to bind the entity\n    to this agreement.\n- type: individual\n  text: You acknowledge that You are at least 18 years of age and you have reached the age of majority in the state\n    or jurisdiction where You live or reside.\nrestricted_uses:\n- summary: Transportation services only\n  text:\
  \ You agree that the uShip Services are for transportation services only and that work that You provide will\n    only involve transportation services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Any identity verification methods we employ are strictly on a best efforts basis and should not be solely\n    relied upon by our users.\nminimum_age:\n  value: '18'\n  text: You acknowledge that You are at least 18 years of age and you have reached the age of majority in the state\n    or jurisdiction where You live or reside.\n"
source_yaml_url: https://artifacts.apis.io/uship/eligibility/uship-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from uShip's own page on 2026-11-10.
synthetic: false
tags:
- Shipping
- Logistics
- Freight
- Marketplace
- Transportation
- AutoTransport
- ltl-freight
- Last Mile Delivery
- Shipment Tracking
- E-Commerce
- Supply Chain
- rate-quotes
---
