---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: I hereby confirm that am a major and a resident of India
  entity_types:
  - text: The words, I, me, my and Customer refer to the person(s) who open the account and shall include both singular and plural.
    type: individual
  minimum_age:
    text: an account may be opened on behalf of a Minor by his natural guardian or by a guardian appointed by a court of Competent Jurisdiction.
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: the bank before opening any deposit account, will carry out a due diligence as required under Know Your Customer guidelines of the bank.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HDFC Bank
provenance_date: '2026-11-09'
provider_name: HDFC Bank
provider_slug: hdfc-bank
slug: hdfc-bank-eligibility
source_date: '2026-11-09'
source_filename: hdfc-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.hdfc.bank.in/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HDFC Bank\naid: hdfc-bank\nurl: https://www.hdfc.bank.in/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: I hereby confirm that am a major and a resident of India\nentity_types:\n- type: individual\n  text: The words, I, me, my and Customer refer to the person(s) who open the account and shall include both singular\n    and plural.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: the bank before opening any deposit account, will carry out a due diligence as required under Know Your\n    Customer\
  \ guidelines of the bank.\nminimum_age:\n  value: null\n  text: an account may be opened on behalf of a Minor by his natural guardian or by a guardian appointed by a court\n    of Competent Jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/hdfc-bank/eligibility/hdfc-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from HDFC Bank's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Finance
- India
- Payments
- Open Banking
---
