---
api_specs:
- filename: copper-financial-account-api-openapi.yml
  format: yaml
  label: Copper Financial Account API
  slug: copper-financial-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-account-api-openapi.yml
- filename: copper-financial-activities-api-openapi.yml
  format: yaml
  label: Copper Financial Activities API
  slug: copper-financial-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-activities-api-openapi.yml
- filename: copper-financial-companies-api-openapi.yml
  format: yaml
  label: Copper Financial Companies API
  slug: copper-financial-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-companies-api-openapi.yml
- filename: copper-financial-custom-fields-api-openapi.yml
  format: yaml
  label: Copper Financial Custom Fields API
  slug: copper-financial-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-custom-fields-api-openapi.yml
- filename: copper-financial-field-layouts-api-openapi.yml
  format: yaml
  label: Copper Financial Field Layouts API
  slug: copper-financial-field-layouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-field-layouts-api-openapi.yml
- filename: copper-financial-leads-api-openapi.yml
  format: yaml
  label: Copper Financial Leads API
  slug: copper-financial-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-leads-api-openapi.yml
- filename: copper-financial-opportunities-api-openapi.yml
  format: yaml
  label: Copper Financial Opportunities API
  slug: copper-financial-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-opportunities-api-openapi.yml
- filename: copper-financial-people-api-openapi.yml
  format: yaml
  label: Copper Financial People API
  slug: copper-financial-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-people-api-openapi.yml
- filename: copper-financial-related-items-api-openapi.yml
  format: yaml
  label: Copper Financial Related Items API
  slug: copper-financial-related-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-related-items-api-openapi.yml
- filename: copper-financial-tags-api-openapi.yml
  format: yaml
  label: Copper Financial Tags API
  slug: copper-financial-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-tags-api-openapi.yml
- filename: copper-financial-tasks-api-openapi.yml
  format: yaml
  label: Copper Financial Tasks API
  slug: copper-financial-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-financial/openapi/copper-financial-tasks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer is not located in a country that is subject to a U.S. government embargo
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this TOS.
    type: business
  minimum_age:
    text: not use, or permit any Authorized User to use, the Service if Customer or such Authorized User, as applicable, is under eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Regulated data (HIPAA/GLBA/PCI)
    text: Customer may not use the Subscription Service where Customer’s usage would be subject to such laws.
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
name: Copper Financial
provenance_date: '2026-11-09'
provider_name: Copper Financial
provider_slug: copper-financial
slug: copper-financial-eligibility
source_date: '2026-11-09'
source_filename: copper-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.copper.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copper Financial\naid: copper-financial\nurl: https://www.copper.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer is not located in a country that is subject to a U.S. government embargo\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this TOS.\nrestricted_uses:\n- summary: Regulated data (HIPAA/GLBA/PCI)\n  text: Customer may not use the Subscription Service where Customer’s usage would be subject\
  \ to such laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: not use, or permit any Authorized User to use, the Service if Customer or such Authorized User, as applicable,\n    is under eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/copper-financial/eligibility/copper-financial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Copper Financial's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Software-as-a-Service
- Sales
- Marketing
---
