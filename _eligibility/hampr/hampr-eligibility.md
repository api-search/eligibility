---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: If you use the Services in the United States, you agree to the following mandatory arbitration provisions
  entity_types:
  - text: If you are using Hampr on behalf of a business or other entity, you represent and warrant that you have the necessary authority to bind that business or entity to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned-country and restricted-party users
    text: User is not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
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
name: hampr
provenance_date: '2026-11-09'
provider_name: hampr
provider_slug: hampr
slug: hampr-eligibility
source_date: '2026-11-09'
source_filename: hampr-eligibility.yml
source_heading: Eligibility
source_page: https://hampr.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hampr\naid: hampr\nurl: https://hampr.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: If you use the Services in the United States, you agree to the following mandatory arbitration provisions\nentity_types:\n- type: business\n  text: If you are using Hampr on behalf of a business or other entity, you represent and warrant that you have\n    the necessary authority to bind that business or entity to these Terms\nrestricted_uses:\n- summary: Sanctioned-country and restricted-party users\n  text: User is not located in a country that is subject to a U.S. Government\
  \ embargo, or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hampr/eligibility/hampr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from hampr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Laundry
- On-Demand
- Delivery
- Consumer Services
- Mobile App
- Gig Economy
- Commercial Laundry
---
