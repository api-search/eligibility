---
api_specs:
- filename: recruitee-c-api-openapi.yml
  format: yaml
  label: Recruitee C API
  slug: recruitee-c-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recruitee/openapi/recruitee-c-api-openapi.yml
- filename: recruitee-i-api-openapi.yml
  format: yaml
  label: Recruitee I API
  slug: recruitee-i-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recruitee/openapi/recruitee-i-api-openapi.yml
- filename: recruitee-offers-api-openapi.yml
  format: yaml
  label: Recruitee Offers API
  slug: recruitee-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recruitee/openapi/recruitee-offers-api-openapi.yml
- filename: recruitee-p-api-openapi.yml
  format: yaml
  label: Recruitee P API
  slug: recruitee-p-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recruitee/openapi/recruitee-p-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Tellent makes no claim that the Services may be lawfully used or that Tellent Content may be uploaded or downloaded to and from the Services outside of the USA, Germany, France and the Netherlands.
  entity_types:
  - text: Subscriber warrants to Tellent that if Subscriber is an individual, he or she is at least 18 years of age.
    type: individual
  - text: The person or legal entity that the Company Account is created for and entering into the Agreement or the successor/assignee of such a legal person
    type: business
  minimum_age:
    text: if Subscriber is an individual, he or she is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Subscriber agrees that it will not use the Services to process or store any content that (a) infringes, violates or otherwise interferes with any copyright or trademark of Tellent or a third party
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
name: Recruitee
provenance_date: '2026-11-10'
provider_name: Recruitee
provider_slug: recruitee
slug: recruitee-eligibility
source_date: '2026-11-10'
source_filename: recruitee-eligibility.yml
source_heading: Eligibility
source_page: https://recruitee.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Recruitee\naid: recruitee\nurl: https://recruitee.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Tellent makes no claim that the Services may be lawfully used or that Tellent Content may be uploaded or\n    downloaded to and from the Services outside of the USA, Germany, France and the Netherlands.\nentity_types:\n- type: individual\n  text: Subscriber warrants to Tellent that if Subscriber is an individual, he or she is at least 18 years of age.\n- type: business\n  text: The person or legal entity that the Company Account is created for and entering\
  \ into the Agreement or the\n    successor/assignee of such a legal person\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Subscriber agrees that it will not use the Services to process or store any content that (a) infringes,\n    violates or otherwise interferes with any copyright or trademark of Tellent or a third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if Subscriber is an individual, he or she is at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/recruitee/eligibility/recruitee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Recruitee's own page on 2026-11-10.
synthetic: false
tags:
- Recruiting
- Applicant Tracking
- Human Resources
- Hiring
- Careers Site
- Tellent
---
