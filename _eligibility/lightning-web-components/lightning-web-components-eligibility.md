---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information about yourself.
    type: individual
  minimum_age:
    text: To create an account, you must be at least 18 years old
    value: '18'
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
name: Lightning Web Components
provenance_date: '2026-11-09'
provider_name: Lightning Web Components
provider_slug: lightning-web-components
slug: lightning-web-components-eligibility
source_date: '2026-11-09'
source_filename: lightning-web-components-eligibility.yml
source_heading: Eligibility
source_page: https://www.salesforce.com/company/legal/sfdc-website-terms-of-service/?bc=OTH
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightning Web Components\naid: lightning-web-components\nurl: https://www.salesforce.com/company/legal/sfdc-website-terms-of-service/?bc=OTH\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information\n    about yourself.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To create an account, you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/lightning-web-components/eligibility/lightning-web-components-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Lightning Web Components's own page on 2026-11-09.
synthetic: false
tags:
- Frontend
- JavaScript
- Lightning Web Components
- Salesforce
- Web Components
- Custom Elements
- Shadow DOM
- Open Source
- UI Framework
- Component Library
---
