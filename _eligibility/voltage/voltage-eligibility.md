---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Site for any illegal or unauthorized purpose
  - summary: Not for regulated industry use
    text: The Site is not tailored to comply with any industry-specific regulations (including, without limitation, the Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
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
name: Voltage
provenance_date: '2026-11-10'
provider_name: Voltage
provider_slug: voltage
slug: voltage-eligibility
source_date: '2026-11-10'
source_filename: voltage-eligibility.yml
source_heading: Eligibility
source_page: https://voltage.cloud/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voltage\naid: voltage\nurl: https://voltage.cloud/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will not use the Site for any illegal or unauthorized purpose\n- summary: Not for regulated industry use\n  text: The Site is not tailored to comply with any industry-specific regulations\
  \ (including, without limitation,\n    the Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act\n    (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/voltage/eligibility/voltage-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Voltage's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Bitcoin
- Lightning Network
- Payments
- Cryptocurrency
- Financial Services
- Wallets
- Infrastructure
- Fintech
- Node Hosting
- Web3
---
