---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 가입신청자가 만 14세 미만인 경우
    value: '14'
  restricted_uses:
  - summary: Identity theft
    text: 타인의 개인(신용)정보 등을 도용하여 회사가 제공하는 서비스를 이용하는 행위
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
name: Finda
provenance_date: '2026-11-09'
provider_name: Finda
provider_slug: finda
slug: finda-eligibility
source_date: '2026-11-09'
source_filename: finda-eligibility.yml
source_heading: Eligibility
source_page: https://finda.co.kr/agreement/service/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finda\naid: finda\nurl: https://finda.co.kr/agreement/service/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Identity theft\n  text: 타인의 개인(신용)정보 등을 도용하여 회사가 제공하는 서비스를 이용하는 행위\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: 가입신청자가 만 14세 미만인 경우\n"
source_yaml_url: https://artifacts.apis.io/finda/eligibility/finda-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Finda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Loans
- Lending
- Loan Comparison
- Personal Finance
- Credit
- South Korea
---
