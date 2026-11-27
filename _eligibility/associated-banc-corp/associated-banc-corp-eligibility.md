---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use only in the United States.
  minimum_age:
    text: Due to the Children's Online Privacy Protection Act, the Site is not intended for use by individuals under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Unlawful internet gambling
    text: Restricted transactions are prohibited from being processed through the Site and/or your account at Associated.
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
name: Associated Bank
provenance_date: '2026-11-09'
provider_name: Associated Bank
provider_slug: associated-banc-corp
slug: associated-banc-corp-eligibility
source_date: '2026-11-09'
source_filename: associated-banc-corp-eligibility.yml
source_heading: Eligibility
source_page: https://www.associatedbank.com/forms-and-disclosures/disclosures/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Associated Bank\naid: associated-banc-corp\nurl: https://www.associatedbank.com/forms-and-disclosures/disclosures/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use only in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful internet gambling\n  text: Restricted transactions are prohibited from being processed through the Site and/or your account at Associated.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Due to the Children's Online Privacy\
  \ Protection Act, the Site is not intended for use by individuals under\n    the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/associated-banc-corp/eligibility/associated-banc-corp-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Associated Bank's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Commercial Banking
- Open Finance
---
