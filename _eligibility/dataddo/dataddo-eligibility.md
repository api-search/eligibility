---
api_specs:
- filename: dataddo-openapi-generated.yml
  format: yaml
  label: Dataddo API
  slug: dataddo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataddo/openapi/_ae-authored/dataddo-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: DATADDO MAKES NO REPRESENTATIONS THAT OUR SERVICES ARE APPROPRIATE OR AVAILABLE FOR USE IN ANY JURISDICTIONS.
  entity_types:
  - text: 'By agreeing to the Terms, you represent and warrant to Dataddo that: (i) you are at least 18 years of age'
    type: individual
  - text: (iv) you have the authority to bind any other person or entity you represent in using these Services.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: No impersonation or harassment
    text: 'You may not (and you may not permit anyone else to) utilize the Services to: Impersonate any person or entity. Stalk, harass, defame, abuse, threaten or otherwise violate the legal rights of others.'
  - summary: No false or illegal activity
    text: Share information that is false or misleading. Engage in any activity that may be considered illegal, unlawful or injurious.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access certain Services you may be required to provide information about yourself (such as identification or contact details) as part of the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dataddo
provenance_date: '2026-11-09'
provider_name: Dataddo
provider_slug: dataddo
slug: dataddo-eligibility
source_date: '2026-11-09'
source_filename: dataddo-eligibility.yml
source_heading: Eligibility
source_page: https://www.dataddo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dataddo\naid: dataddo\nurl: https://www.dataddo.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: DATADDO MAKES NO REPRESENTATIONS THAT OUR SERVICES ARE APPROPRIATE OR AVAILABLE FOR USE IN ANY JURISDICTIONS.\nentity_types:\n- type: individual\n  text: 'By agreeing to the Terms, you represent and warrant to Dataddo that: (i) you are at least 18 years of age'\n- type: business\n  text: (iv) you have the authority to bind any other person or entity you represent in using these Services.\nrestricted_uses:\n- summary: No impersonation or harassment\n  text: 'You may not (and\
  \ you may not permit anyone else to) utilize the Services to: Impersonate any person or\n    entity. Stalk, harass, defame, abuse, threaten or otherwise violate the legal rights of others.'\n- summary: No false or illegal activity\n  text: Share information that is false or misleading. Engage in any activity that may be considered illegal, unlawful\n    or injurious.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access certain Services you may be required to provide information about yourself (such as identification\n    or contact details) as part of the registration process\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/dataddo/eligibility/dataddo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Dataddo's own page on 2026-11-09.
synthetic: false
tags:
- Data Integration
- API Platform
- Artificial Intelligence
- Real-Time
- ETL
---
