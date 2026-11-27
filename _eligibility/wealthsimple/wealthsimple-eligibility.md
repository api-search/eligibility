---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: In order to use and access the Platform, you must be a Canadian resident.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and embargoes
    text: you are not subject to economic or trade sanctions, and you are not located in a country subject to sanctions imposed by Canada, the United States, the United Kingdom, or the European Union
  - summary: Criminal or politically exposed persons
    text: you are not, or are not alleged to be, a member of, or associated with, a criminal organization or persons who are known to be associated with a criminal organization
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
name: Wealthsimple
provenance_date: '2026-11-10'
provider_name: Wealthsimple
provider_slug: wealthsimple
slug: wealthsimple-eligibility
source_date: '2026-11-10'
source_filename: wealthsimple-eligibility.yml
source_heading: Eligibility
source_page: https://www.wealthsimple.com/en-ca/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wealthsimple\naid: wealthsimple\nurl: https://www.wealthsimple.com/en-ca/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: In order to use and access the Platform, you must be a Canadian resident.\nentity_types: []\nrestricted_uses:\n- summary: Sanctions and embargoes\n  text: you are not subject to economic or trade sanctions, and you are not located in a country subject to sanctions\n    imposed by Canada, the United States, the United Kingdom, or the European Union\n- summary: Criminal or politically exposed persons\n  text: you are not, or are not alleged to be,\
  \ a member of, or associated with, a criminal organization or persons\n    who are known to be associated with a criminal organization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wealthsimple/eligibility/wealthsimple-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Wealthsimple's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Investing
- Wealth Management
- Cryptocurrency
- Trading
- Tax
- Banking
- Canada
---
