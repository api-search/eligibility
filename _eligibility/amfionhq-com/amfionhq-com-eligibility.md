---
api_specs:
- filename: amfionhq-com-fleet-api-openapi.yml
  format: yaml
  label: amfionhq-com Fleet API
  slug: amfionhq-com-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-fleet-api-openapi.yml
- filename: amfionhq-com-tenants-api-openapi.yml
  format: yaml
  label: amfionhq-com Tenants API
  slug: amfionhq-com-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-tenants-api-openapi.yml
- filename: amfionhq-com-tools-api-openapi.yml
  format: yaml
  label: amfionhq-com Tools API
  slug: amfionhq-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-tools-api-openapi.yml
- filename: amfionhq-com-usage-api-openapi.yml
  format: yaml
  label: amfionhq-com Usage API
  slug: amfionhq-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-usage-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We currently serve US-based businesses.
  entity_types:
  - text: Be at least 18 years old or the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: Be at least 18 years old or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: EEA/UK/Swiss personal data transfers
    text: Do not use the Service for personal data whose processing requires European Economic Area, UK, or Swiss transfer arrangements until we have confirmed the arrangements for your use in writing.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: An account for a business outside the United States, or one that expects to use the Service with personal data of people in the European Economic Area, the UK, or Switzerland, goes live only after we review it.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: amfionhq-com
provenance_date: '2026-11-09'
provider_name: amfionhq-com
provider_slug: amfionhq-com
slug: amfionhq-com-eligibility
source_date: '2026-11-09'
source_filename: amfionhq-com-eligibility.yml
source_heading: Eligibility
source_page: https://amfionhq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: amfionhq-com\naid: amfionhq-com\nurl: https://amfionhq.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We currently serve US-based businesses.\nentity_types:\n- type: individual\n  text: Be at least 18 years old or the age of majority in your jurisdiction\nrestricted_uses:\n- summary: EEA/UK/Swiss personal data transfers\n  text: Do not use the Service for personal data whose processing requires European Economic Area, UK, or Swiss\n    transfer arrangements until we have confirmed the arrangements for your use in writing.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: An account for a business outside the United States, or one that expects to use the Service with personal\n    data of people in the European Economic Area, the UK, or Switzerland, goes live only after we review it.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/amfionhq-com/eligibility/amfionhq-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from amfionhq-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Front Desk
- Booking
- Automation
---
