---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This policy applies to all entities which are granted a login to a Lumin Digital digital banking site
    type: business
  - source: https://lumindigital.com/terms-of-use/
    text: It is not intended for consumers seeking access to banking products or services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, fraudulent or harmful use
    text: Client agrees not to utilize any digital banking interface or software to encourage, promote, facilitate or instruct others to use, Lumin Digital’s services for any illegal, harmful, fraudulent, infringing or offensive use
  - source: https://lumindigital.com/terms-of-use/
    summary: Not for consumer banking access
    text: It is not intended for consumers seeking access to banking products or services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Client shall dictate and have final authority to authorize and approve prospective users through Know Your Customer (KYC), Office of Foreign Asset Control (OFAC), and other mandated screening procedures.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lumin Digital
provenance_date: '2026-11-10'
provider_name: Lumin Digital
provider_slug: lumin-digital
slug: lumin-digital-eligibility
source_date: '2026-11-10'
source_filename: lumin-digital-eligibility.yml
source_heading: Eligibility
source_page: https://lumindigital.com/aup/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lumin Digital\naid: lumin-digital\nurl: https://lumindigital.com/aup/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://lumindigital.com/aup/\n  - https://lumindigital.com/terms-of-use/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This policy applies to all entities which are granted a login to a Lumin Digital digital banking site\n- type: individual\n  text: It is not intended for consumers seeking access to banking products or services.\n  source: https://lumindigital.com/terms-of-use/\nrestricted_uses:\n- summary: Illegal, fraudulent or harmful use\n \
  \ text: Client agrees not to utilize any digital banking interface or software to encourage, promote, facilitate\n    or instruct others to use, Lumin Digital’s services for any illegal, harmful, fraudulent, infringing or offensive\n    use\n- summary: Not for consumer banking access\n  text: It is not intended for consumers seeking access to banking products or services.\n  source: https://lumindigital.com/terms-of-use/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Client shall dictate and have final authority to authorize and approve prospective users through Know Your\n    Customer (KYC), Office of Foreign Asset Control (OFAC), and other mandated screening procedures.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lumin-digital/eligibility/lumin-digital-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Lumin Digital's own page on 2026-11-10.
synthetic: false
tags:
- Digital Banking
- Banking
- Credit Union
- Financial Services
- Fintech
- Core Banking
- Digital Account Opening
- Payments
- Commercial Banking
- Software-as-a-Service
---
