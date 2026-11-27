---
api_specs:
- filename: avis-budget-car-availability-api-openapi.yml
  format: yaml
  label: Avis Budget Group Car Availability API
  slug: avis-budget-car-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avis-budget/openapi/avis-budget-car-availability-api-openapi.yml
- filename: avis-budget-car-locations-api-openapi.yml
  format: yaml
  label: Avis Budget Group Car Locations API
  slug: avis-budget-car-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avis-budget/openapi/avis-budget-car-locations-api-openapi.yml
- filename: avis-budget-car-reservation-api-openapi.yml
  format: yaml
  label: Avis Budget Group Car Reservation API
  slug: avis-budget-car-reservation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avis-budget/openapi/avis-budget-car-reservation-api-openapi.yml
- filename: avis-budget-terms-and-conditions-api-openapi.yml
  format: yaml
  label: Avis Budget Group Terms And Conditions API
  slug: avis-budget-terms-and-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avis-budget/openapi/avis-budget-terms-and-conditions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are hereby prohibited from accessing or using the Website from any territory where the Website or any of the features, functionality, tools, content thereof, is illegal.
  entity_types:
  - text: You agree that you will access and use the Website for your personal use only.
    type: individual
  - text: If you are accepting or agreeing to the Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to act on behalf of and bind that entity to the Terms.
    type: business
  minimum_age:
    text: if you are not able to form legally binding contracts (for example, if you are under 18)
    value: '18'
  restricted_uses:
  - summary: Political campaigning and solicitation
    text: for political campaigning, recruiting votes or soliciting donations or other support for legislative or other initiatives
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
name: Avis Budget Group
provenance_date: '2026-11-09'
provider_name: Avis Budget Group
provider_slug: avis-budget
slug: avis-budget-eligibility
source_date: '2026-11-09'
source_filename: avis-budget-eligibility.yml
source_heading: Eligibility
source_page: https://www.avisbudgetgroup.com/home/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avis Budget Group\naid: avis-budget\nurl: https://www.avisbudgetgroup.com/home/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are hereby prohibited from accessing or using the Website from any territory where the Website or any\n    of the features, functionality, tools, content thereof, is illegal.\nentity_types:\n- type: individual\n  text: You agree that you will access and use the Website for your personal use only.\n- type: business\n  text: If you are accepting or agreeing to the Terms on behalf of a company or other legal entity, you represent\n    and warrant\
  \ that you have the authority to act on behalf of and bind that entity to the Terms.\nrestricted_uses:\n- summary: Political campaigning and solicitation\n  text: for political campaigning, recruiting votes or soliciting donations or other support for legislative or\n    other initiatives\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are not able to form legally binding contracts (for example, if you are under 18)\n"
source_yaml_url: https://artifacts.apis.io/avis-budget/eligibility/avis-budget-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Avis Budget Group's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Car Rental
- Travel
- Mobility
- Fleet Management
- Transportation
- Reservations
- Vehicle Rental
- Partner API
- Hospitality
---
