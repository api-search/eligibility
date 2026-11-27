---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Sites from jurisdictions where the contents of the Sites are illegal or penalized is prohibited.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the Services, you must create an Account and agree to these Terms of Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Included Health
provenance_date: '2026-11-09'
provider_name: Included Health
provider_slug: included-health
slug: included-health-eligibility
source_date: '2026-11-09'
source_filename: included-health-eligibility.yml
source_heading: Eligibility
source_page: https://includedhealth.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Included Health\naid: included-health\nurl: https://includedhealth.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Sites from jurisdictions where the contents of the Sites are illegal or penalized is prohibited.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use the Services, you must create an Account and agree to these Terms of Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/included-health/eligibility/included-health-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Included Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Application
- Healthcare
- Virtual Care
- Telehealth
- Healthcare Navigation
- Health Plans
- Care Coordination
---
