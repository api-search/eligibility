---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Etleap from its facilities in the United States of America. Etleap makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: The Services are provided to those business customers who subscribe to such Services pursuant to a Master Services Agreement, Subscription Agreement or another agreement
    type: business
  minimum_age:
    text: You affirm that You are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: Users under 13
    text: Etleap is not intended for children under 13. If You are under 13 years of age, then please do not use the Services or the Website.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be authorized by the company who entered into a Service Agreement with Etleap to use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Etleap
provenance_date: '2026-11-09'
provider_name: Etleap
provider_slug: etleap
slug: etleap-eligibility
source_date: '2026-11-09'
source_filename: etleap-eligibility.yml
source_heading: Eligibility
source_page: https://etleap.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Etleap\naid: etleap\nurl: https://etleap.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Etleap from its facilities in the United States of America. Etleap\n    makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: The Services are provided to those business customers who subscribe to such Services pursuant to a Master\n    Services Agreement, Subscription Agreement or another agreement\nrestricted_uses:\n- summary: Users under 13\n \
  \ text: Etleap is not intended for children under 13. If You are under 13 years of age, then please do not use the\n    Services or the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be authorized by the company who entered into a Service Agreement with Etleap to use the Services\nminimum_age:\n  value: '18'\n  text: You affirm that You are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/etleap/eligibility/etleap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Etleap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- ETL
- ELT
- Data Pipeline
- Data Warehouse
- Data Lake
- Apache Iceberg
- Analytics
---
