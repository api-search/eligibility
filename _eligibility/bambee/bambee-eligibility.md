---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (e) access the service outside of the United States of America (but in any event, if You do, that You will be liable for all legal compliance with such access)
  entity_types:
  - text: As an Employee, You represent and understand You are responsible for Your use of our Services.
    type: individual
  - text: As an Employer You represent and understand that You are responsible for Your use as well as all of Your Employee's use of Our Services.
    type: business
  minimum_age:
    text: access the Service if you are under 18 years of age
    value: '18'
  restricted_uses:
  - summary: Restricted business activities
    text: including for engaging in what Bambee considers to be restricted business activities such as gambling, sale of certain drugs or paraphernalia, guns or ammunition, flammable or combustible substances, adult entertainment, virtual currency, counterfeit products
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right, in Our sole discretion, to accept or reject Your registration to use Our Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bambee
provenance_date: '2026-11-09'
provider_name: Bambee
provider_slug: bambee
slug: bambee-eligibility
source_date: '2026-11-09'
source_filename: bambee-eligibility.yml
source_heading: Eligibility
source_page: https://www.bambee.com/legal/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bambee\naid: bambee\nurl: https://www.bambee.com/legal/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: (e) access the service outside of the United States of America (but in any event, if You do, that You will\n    be liable for all legal compliance with such access)\nentity_types:\n- type: individual\n  text: As an Employee, You represent and understand You are responsible for Your use of our Services.\n- type: business\n  text: As an Employer You represent and understand that You are responsible for Your use as well as all of Your\n    Employee's use of\
  \ Our Services.\nrestricted_uses:\n- summary: Restricted business activities\n  text: including for engaging in what Bambee considers to be restricted business activities such as gambling, sale\n    of certain drugs or paraphernalia, guns or ammunition, flammable or combustible substances, adult entertainment,\n    virtual currency, counterfeit products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right, in Our sole discretion, to accept or reject Your registration to use Our Services\nminimum_age:\n  value: '18'\n  text: access the Service if you are under 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/bambee/eligibility/bambee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bambee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Payroll
- HR Compliance
- Small Business
- Fintech
---
