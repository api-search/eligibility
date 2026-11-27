---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not (i) located in, or a resident or national of, any country subject to U.S. embargo or sanctions
  entity_types:
  - text: if Customer is using these Services on behalf of an organization, entity, or group, that Customer is authorized to accept these Terms.
    type: business
  minimum_age:
    text: The Customer certifies that they are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: Customer agrees to comply with all applicable export control laws and regulations
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
name: DreamHost DreamObjects
provenance_date: '2026-11-09'
provider_name: DreamHost DreamObjects
provider_slug: dreamhost
slug: dreamhost-eligibility
source_date: '2026-11-09'
source_filename: dreamhost-eligibility.yml
source_heading: Eligibility
source_page: https://www.dreamhost.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DreamHost DreamObjects\naid: dreamhost\nurl: https://www.dreamhost.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not (i) located in, or a resident or national of, any country\n    subject to U.S. embargo or sanctions\nentity_types:\n- type: business\n  text: if Customer is using these Services on behalf of an organization, entity, or group, that Customer is authorized\n    to accept these Terms.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Customer agrees to comply with all applicable\
  \ export control laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Customer certifies that they are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/dreamhost/eligibility/dreamhost-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from DreamHost DreamObjects's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hosting
- Cloud
- Domains
---
