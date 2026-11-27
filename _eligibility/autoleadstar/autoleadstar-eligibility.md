---
api_specs:
- filename: autoleadstar-activities-api-openapi.yml
  format: yaml
  label: AutoLeadStar Activities API
  slug: autoleadstar-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-activities-api-openapi.yml
- filename: autoleadstar-appointments-api-openapi.yml
  format: yaml
  label: AutoLeadStar Appointments API
  slug: autoleadstar-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-appointments-api-openapi.yml
- filename: autoleadstar-audiences-api-openapi.yml
  format: yaml
  label: AutoLeadStar Audiences API
  slug: autoleadstar-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-audiences-api-openapi.yml
- filename: autoleadstar-consents-api-openapi.yml
  format: yaml
  label: AutoLeadStar Consents API
  slug: autoleadstar-consents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-consents-api-openapi.yml
- filename: autoleadstar-leads-api-openapi.yml
  format: yaml
  label: AutoLeadStar Leads API
  slug: autoleadstar-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-leads-api-openapi.yml
- filename: autoleadstar-shoppers-api-openapi.yml
  format: yaml
  label: AutoLeadStar Shoppers API
  slug: autoleadstar-shoppers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-shoppers-api-openapi.yml
- filename: autoleadstar-tasks-api-openapi.yml
  format: yaml
  label: AutoLeadStar Tasks API
  slug: autoleadstar-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoleadstar/openapi/autoleadstar-tasks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY, AND CAPACITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD, BUT IN ANY EVENT OF A LEGAL AGE TO FORM A BINDING CONTRACT.
    value: '18'
  restricted_uses:
  - summary: Minors barred from Website
    text: MINORS ARE NOT PERMITTED TO ACCESS OR USE THE WEBSITE.
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
name: AutoLeadStar
provenance_date: '2026-11-09'
provider_name: AutoLeadStar
provider_slug: autoleadstar
slug: autoleadstar-eligibility
source_date: '2026-11-09'
source_filename: autoleadstar-eligibility.yml
source_heading: Eligibility
source_page: https://www.fullpath.com/legal-and-trust/?nav=websiteterms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoLeadStar\naid: autoleadstar\nurl: https://www.fullpath.com/legal-and-trust/?nav=websiteterms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY,\n    AND CAPACITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Minors barred from Website\n  text: MINORS ARE NOT PERMITTED TO ACCESS OR USE THE WEBSITE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD, BUT IN ANY EVENT OF A LEGAL AGE TO FORM A BINDING\n    CONTRACT.\n"
source_yaml_url: https://artifacts.apis.io/autoleadstar/eligibility/autoleadstar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AutoLeadStar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Customer Data Platform
- Marketing Automation
- Dealership
- Advertising
- Artificial Intelligence
- Consent Management
- CRM
- Israel
---
