---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Members or customers of the Prosper community must be U.S. Residents with a valid social security number that are 18 years of age or older.
  minimum_age:
    text: Children under the age of 18 are not eligible to participate in the offerings on the Site.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for particular products or services is subject to final determination by Prosper.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prosper
provenance_date: '2026-11-10'
provider_name: Prosper
provider_slug: prosper
slug: prosper-eligibility
source_date: '2026-11-10'
source_filename: prosper-eligibility.yml
source_heading: Eligibility
source_page: https://www.prosper.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prosper\naid: prosper\nurl: https://www.prosper.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Members or customers of the Prosper community must be U.S. Residents with a valid social security number\n    that are 18 years of age or older.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility for particular products or services is subject to final determination by Prosper.\nminimum_age:\n  value: '18'\n  text: Children under the age of 18 are not eligible to participate in\
  \ the offerings on the Site.\n"
source_yaml_url: https://artifacts.apis.io/prosper/eligibility/prosper-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Prosper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Peer-to-Peer Lending
- Marketplace Lending
- Investing
- Personal Loans
- Consumer Credit
- Financial Services
---
