---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where the service is used for business purposes, the Customer shall indemnify Bootify against third-party claims and reasonable costs arising from unlawful Project Data supplied by the Customer or a material breach of this section.
    type: business
  - text: If the Customer is a consumer, this choice of law does not deprive the Customer of the protection provided by mandatory laws of the country in which the Customer has their habitual residence.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal data in project data
    text: The Customer must not submit personal data relating to identifiable individuals as project data or otherwise use the service to process personal data on behalf of third parties.
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
name: Bootify
provenance_date: '2026-11-09'
provider_name: Bootify
provider_slug: bootify-io
slug: bootify-io-eligibility
source_date: '2026-11-09'
source_filename: bootify-io-eligibility.yml
source_heading: Eligibility
source_page: https://bootify.io/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bootify\naid: bootify-io\nurl: https://bootify.io/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Where the service is used for business purposes, the Customer shall indemnify Bootify against third-party\n    claims and reasonable costs arising from unlawful Project Data supplied by the Customer or a material breach\n    of this section.\n- type: individual\n  text: If the Customer is a consumer, this choice of law does not deprive the Customer of the protection provided\n    by mandatory laws of the country in which the Customer\
  \ has their habitual residence.\nrestricted_uses:\n- summary: Personal data in project data\n  text: The Customer must not submit personal data relating to identifiable individuals as project data or otherwise\n    use the service to process personal data on behalf of third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bootify-io/eligibility/bootify-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bootify's own page on 2026-11-09.
synthetic: false
tags:
- Spring Boot
- Code Generation
- API Generation
- Database Design
- Frontend Integration
---
