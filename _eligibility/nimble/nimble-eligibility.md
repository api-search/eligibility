---
api_specs:
- filename: nimble-activities-api-openapi.yml
  format: yaml
  label: Nimble Activities API
  slug: nimble-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-activities-api-openapi.yml
- filename: nimble-contacts-api-openapi.yml
  format: yaml
  label: Nimble Contacts API
  slug: nimble-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-contacts-api-openapi.yml
- filename: nimble-contacts-fields-api-openapi.yml
  format: yaml
  label: Nimble Contacts Fields API
  slug: nimble-contacts-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-contacts-fields-api-openapi.yml
- filename: nimble-contacts-pipelines-api-openapi.yml
  format: yaml
  label: Nimble Contacts Pipelines API
  slug: nimble-contacts-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-contacts-pipelines-api-openapi.yml
- filename: nimble-deals-api-openapi.yml
  format: yaml
  label: Nimble Deals API
  slug: nimble-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-api-openapi.yml
- filename: nimble-deals-fields-api-openapi.yml
  format: yaml
  label: Nimble Deals Fields API
  slug: nimble-deals-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-fields-api-openapi.yml
- filename: nimble-deals-pipelines-api-openapi.yml
  format: yaml
  label: Nimble Deals Pipelines API
  slug: nimble-deals-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-pipelines-api-openapi.yml
- filename: nimble-deals-pipelines-fields-api-openapi.yml
  format: yaml
  label: Nimble Deals Pipelines Fields API
  slug: nimble-deals-pipelines-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-pipelines-fields-api-openapi.yml
- filename: nimble-leads-api-openapi.yml
  format: yaml
  label: Nimble Leads API
  slug: nimble-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-leads-api-openapi.yml
- filename: nimble-messages-api-openapi.yml
  format: yaml
  label: Nimble Messages API
  slug: nimble-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-messages-api-openapi.yml
- filename: nimble-tasks-api-openapi.yml
  format: yaml
  label: Nimble Tasks API
  slug: nimble-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-tasks-api-openapi.yml
- filename: nimble-users-api-openapi.yml
  format: yaml
  label: Nimble Users API
  slug: nimble-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If Customer resides in a country embargoed by the United States, Customer agrees Customer will not engage in commercial activities or operate or develop an application in connection with or using the Services.
  entity_types:
  - text: Team Accounts may be purchased by a company or an individual for the purpose of adding numerous Customers together under one common Nimble Team Account.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content and associations
    text: 'Customer will not use, associate or link the Services in connection with a website or content including any of the following: (i) racial, ethnic, gender, age, religious, political, or sexual orientation discrimination;'
  - summary: Unlawful or harmful use
    text: Customer agrees not to use the Services for illegal purposes or for the transmission of material that is unlawful, harassing, libelous, invasive of another person’s privacy, abusive, threatening, harmful, vulgar, pornographic, obscene, or otherwise objectionable
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
name: Nimble
provenance_date: '2026-11-10'
provider_name: Nimble
provider_slug: nimble
slug: nimble-eligibility
source_date: '2026-11-10'
source_filename: nimble-eligibility.yml
source_heading: Eligibility
source_page: https://www.nimble.com/company/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nimble\naid: nimble\nurl: https://www.nimble.com/company/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If Customer resides in a country embargoed by the United States, Customer agrees Customer will not engage\n    in commercial activities or operate or develop an application in connection with or using the Services.\nentity_types:\n- type: business\n  text: Team Accounts may be purchased by a company or an individual for the purpose of adding numerous Customers\n    together under one common Nimble Team Account.\nrestricted_uses:\n- summary: Prohibited content\
  \ and associations\n  text: 'Customer will not use, associate or link the Services in connection with a website or content including\n    any of the following: (i) racial, ethnic, gender, age, religious, political, or sexual orientation discrimination;'\n- summary: Unlawful or harmful use\n  text: Customer agrees not to use the Services for illegal purposes or for the transmission of material that is\n    unlawful, harassing, libelous, invasive of another person’s privacy, abusive, threatening, harmful, vulgar,\n    pornographic, obscene, or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nimble/eligibility/nimble-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Nimble's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Contact Management
- Relationship Management
- Marketing Automation
- Pipeline Management
- Small Business
- Email Marketing
- Sales Automation
- Lead Management
---
