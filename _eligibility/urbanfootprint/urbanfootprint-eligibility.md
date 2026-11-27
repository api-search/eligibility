---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: in the case of an individual accepting this Agreement on his or her own behalf
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  - text: 12.2 United States Government Users . The Platform is commercial computer software as defined in FAR 2.101.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: You may not access the Services if You are Our direct competitor, except with Our prior written consent.
  - summary: No monitoring or benchmarking access
    text: You may not access the Services for purposes of monitoring their availability, performance or functionality, or for any other benchmarking or competitive purposes.
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
name: UrbanFootprint
provenance_date: '2026-11-10'
provider_name: UrbanFootprint
provider_slug: urbanfootprint
slug: urbanfootprint-eligibility
source_date: '2026-11-10'
source_filename: urbanfootprint-eligibility.yml
source_heading: Eligibility
source_page: https://urbanfootprint.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UrbanFootprint\naid: urbanfootprint\nurl: https://urbanfootprint.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: in the case of an individual accepting this Agreement on his or her own behalf\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\n- type: government\n  text: 12.2 United States Government Users . The Platform is commercial computer software as defined in FAR 2.101.\nrestricted_uses:\n\
  - summary: Direct competitors barred\n  text: You may not access the Services if You are Our direct competitor, except with Our prior written consent.\n- summary: No monitoring or benchmarking access\n  text: You may not access the Services for purposes of monitoring their availability, performance or functionality,\n    or for any other benchmarking or competitive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/urbanfootprint/eligibility/urbanfootprint-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from UrbanFootprint's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Climate
- Geospatial
- Urban Planning
- Data
- Analytics
- Resilience
- Mapping
---
