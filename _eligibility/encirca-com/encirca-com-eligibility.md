---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must also provide the name of an authorized person for contact purposes in the case of an Registered Name Holder that is an organization, association, or corporation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted .CPA domain use
    text: Reseller acknowledges that the .CPA TLD is intended exclusively for firms and individuals holding an active license for Certified Public Accountants throughout the term of the .CPA domain name registrations.
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
name: EnCirca
provenance_date: '2026-11-09'
provider_name: EnCirca
provider_slug: encirca-com
slug: encirca-com-eligibility
source_date: '2026-11-09'
source_filename: encirca-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.encirca.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EnCirca\naid: encirca-com\nurl: https://www.encirca.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must also provide the name of an authorized person for contact purposes in the case of an Registered\n    Name Holder that is an organization, association, or corporation.\nrestricted_uses:\n- summary: Restricted .CPA domain use\n  text: Reseller acknowledges that the .CPA TLD is intended exclusively for firms and individuals holding an active\n    license for Certified Public Accountants throughout\
  \ the term of the .CPA domain name registrations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/encirca-com/eligibility/encirca-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from EnCirca's own page on 2026-11-09.
synthetic: false
tags:
- Domain Registrar
- icann-accredited
- verified-tlds
- Web Hosting
- SSL
---
