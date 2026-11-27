---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither you, anyone for whom you are an agent or nominee, your Organization, nor anyone who controls your Organization(s) are (i) the target of any laws administered by the United States Department of the Treasury's Office of Foreign Assets Control
  entity_types:
  - text: You are at least 18 years old (in the case of a natural person) and legally able to form a binding contract with Unchained
    type: individual
  - text: By applying for any of the Unchained Services on behalf of an Organization, you represent and warrant that you are duly authorized to do so by the entity that is your Organization
    type: business
  minimum_age:
    text: To access and use the Site and the other Unchained Services, you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No consumer, personal, family or household use
    text: You may not use the Unchained Site or the Unchained Services for consumer, personal, family, or household purposes.
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: Unchained conducts full anti-money laundering (AML) and know your customer (KYC) verification checks on users of the Unchained Services. In the case of an Organization, Unchained may conduct AML and KYC checks on the Organization itself
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unchained Capital
provenance_date: '2026-11-10'
provider_name: Unchained Capital
provider_slug: unchained-capital
slug: unchained-capital-eligibility
source_date: '2026-11-10'
source_filename: unchained-capital-eligibility.yml
source_heading: Eligibility
source_page: https://www.unchained.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unchained Capital\naid: unchained-capital\nurl: https://www.unchained.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Neither you, anyone for whom you are an agent or nominee, your Organization, nor anyone who controls your\n    Organization(s) are (i) the target of any laws administered by the United States Department of the Treasury's\n    Office of Foreign Assets Control\nentity_types:\n- type: individual\n  text: You are at least 18 years old (in the case of a natural person) and legally able to form a binding contract\n    with Unchained\n\
  - type: business\n  text: By applying for any of the Unchained Services on behalf of an Organization, you represent and warrant that\n    you are duly authorized to do so by the entity that is your Organization\nrestricted_uses:\n- summary: No consumer, personal, family or household use\n  text: You may not use the Unchained Site or the Unchained Services for consumer, personal, family, or household\n    purposes.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: Unchained conducts full anti-money laundering (AML) and know your customer (KYC) verification checks on\n    users of the Unchained Services. In the case of an Organization, Unchained may conduct AML and KYC checks on\n    the Organization itself\nminimum_age:\n  value: '18'\n  text: To access and use the Site and the other Unchained Services, you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/unchained-capital/eligibility/unchained-capital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Unchained Capital's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Bitcoin
- Cryptocurrency
- Financial Services
- Custody
- Wealth Management
- Lending
- Retirement
- Trading
- Open Source
---
