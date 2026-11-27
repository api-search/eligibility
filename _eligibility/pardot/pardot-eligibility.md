---
api_specs:
- filename: pardot-objects-api-openapi.yml
  format: yaml
  label: Salesforce Marketing Cloud Account Engagement (Pardot) Objects API
  slug: pardot-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pardot/openapi/pardot-objects-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information about yourself.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to create an account and specify a password in order to use certain services or features on the Sites.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Salesforce Marketing Cloud Account Engagement (Pardot)
provenance_date: '2026-11-10'
provider_name: Salesforce Marketing Cloud Account Engagement (Pardot)
provider_slug: pardot
slug: pardot-eligibility
source_date: '2026-11-10'
source_filename: pardot-eligibility.yml
source_heading: Eligibility
source_page: https://www.salesforce.com/company/legal/sfdc-website-terms-of-service/?bc=OTH
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Salesforce Marketing Cloud Account Engagement (Pardot)\naid: pardot\nurl: https://www.salesforce.com/company/legal/sfdc-website-terms-of-service/?bc=OTH\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to create an account and specify a password in order to use certain services or features\n    on the Sites.\nminimum_age:\n  value: '18'\n  text: To create an account, you must be at least 18 years old and you must provide truthful and accurate\
  \ information\n    about yourself.\n"
source_yaml_url: https://artifacts.apis.io/pardot/eligibility/pardot-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Salesforce Marketing Cloud Account Engagement (Pardot)'s own page on 2026-11-10.
synthetic: false
tags:
- Marketing Automation
- B2B Marketing
- Lead Generation
- Email Marketing
- Salesforce
- Account Engagement
---
