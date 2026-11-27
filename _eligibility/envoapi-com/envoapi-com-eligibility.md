---
api_specs:
- filename: envoapi-com-openapi-generated.yml
  format: yaml
  label: envoapi-com API
  slug: envoapi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/envoapi-com/openapi/_ae-authored/envoapi-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that it is not located in, organized under the laws of, or ordinarily resident in a sanctioned jurisdiction, and is not listed on any applicable restricted party list.
  entity_types:
  - text: If you are using the Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity to these Terms.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive or regulated decisions
    text: 'Customer must not use the Services or Output Data as the sole or determinative basis for decisions involving: credit, lending, insurance, housing, education admissions, government benefits, healthcare eligibility, criminal justice, or similar eligibility determinations'
  - summary: Consumer reports
    text: The Services are not consumer reporting services and Output Data is not a consumer report.
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
name: envoapi-com
provenance_date: '2026-11-09'
provider_name: envoapi-com
provider_slug: envoapi-com
slug: envoapi-com-eligibility
source_date: '2026-11-09'
source_filename: envoapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://envoapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: envoapi-com\naid: envoapi-com\nurl: https://envoapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that it is not located in, organized under the laws of, or ordinarily resident in a\n    sanctioned jurisdiction, and is not listed on any applicable restricted party list.\nentity_types:\n- type: individual\n  text: If you are using the Services on behalf of a company or other legal entity, you represent that you have\n    authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Sensitive or regulated decisions\n  text: 'Customer must\
  \ not use the Services or Output Data as the sole or determinative basis for decisions involving:\n    credit, lending, insurance, housing, education admissions, government benefits, healthcare eligibility, criminal\n    justice, or similar eligibility determinations'\n- summary: Consumer reports\n  text: The Services are not consumer reporting services and Output Data is not a consumer report.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/envoapi-com/eligibility/envoapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from envoapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Data Enrichment
- B2B
- LinkedIn
- Email Verification
---
