---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Export/import clause refers to U.S. and foreign import and export control laws without naming countries.
  entity_types:
  - text: If you create or use an account, you are declaring that you are at least 18 years old.
    type: individual
  - text: IF YOU ARE ACCEPTING THIS SOFTWARE-AS-A-SERVICE TERMS OF USE (“AGREEMENT”) ON BEHALF OF A COMPANY, AS AN INDIVIDUAL OR OTHER LEGAL ENTITY (CUSTOMER”)
    type: business
  minimum_age:
    text: If you create or use an account, you are declaring that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or unlawful use
    text: use the Services for any illegal purposes or in a way that would be unlawful
  - summary: Vulnerability probing without authorization
    text: to probe, scan or test for vulnerabilities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Trial participation will be subject to qualification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BreachLock
provenance_date: '2026-11-09'
provider_name: BreachLock
provider_slug: breachlock
slug: breachlock-eligibility
source_date: '2026-11-09'
source_filename: breachlock-eligibility.yml
source_heading: Eligibility
source_page: https://www.breachlock.com/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BreachLock\naid: breachlock\nurl: https://www.breachlock.com/about/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Export/import clause refers to U.S. and foreign import and export control laws without naming countries.\nentity_types:\n- type: individual\n  text: If you create or use an account, you are declaring that you are at least 18 years old.\n- type: business\n  text: IF YOU ARE ACCEPTING THIS SOFTWARE-AS-A-SERVICE TERMS OF USE (“AGREEMENT”) ON BEHALF OF A COMPANY, AS AN\n    INDIVIDUAL OR OTHER LEGAL ENTITY (CUSTOMER”)\nrestricted_uses:\n- summary: Illegal or\
  \ unlawful use\n  text: use the Services for any illegal purposes or in a way that would be unlawful\n- summary: Vulnerability probing without authorization\n  text: to probe, scan or test for vulnerabilities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Trial participation will be subject to qualification.\nminimum_age:\n  value: '18'\n  text: If you create or use an account, you are declaring that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/breachlock/eligibility/breachlock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from BreachLock's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Penetration Testing
- Attack Surface Management
- Red Team
- Software-as-a-Service
---
