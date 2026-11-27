---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are located in the United States, the following terms... are offered to you by SecureW2, Inc. If you are not located in the United States, these Terms and Conditions are offered to you by SecureW2, B.V.
  entity_types:
  - text: IF YOU ARE USING ANY SERVICE AS AN EMPLOYEE, CONTRACTOR, OR AGENT OF A CORPORATION, PARTNERSHIP OR SIMILAR ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited Customer Content
    text: 'Customer Content may not: (i) be defamatory, harmful to minors, obscene, indecent, pornographic, libelous, threatening, harassing, false, misleading or inaccurate'
  - summary: No health, financial or government ID data
    text: (vi) contain any health, medical, financial, credit card or other payment information or any information of any person or any government-issued identifying information
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
name: SecureW2
provenance_date: '2026-11-10'
provider_name: SecureW2
provider_slug: securew2
slug: securew2-eligibility
source_date: '2026-11-10'
source_filename: securew2-eligibility.yml
source_heading: Eligibility
source_page: https://securew2.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SecureW2\naid: securew2\nurl: https://securew2.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you are located in the United States, the following terms... are offered to you by SecureW2, Inc. If\n    you are not located in the United States, these Terms and Conditions are offered to you by SecureW2, B.V.\nentity_types:\n- type: business\n  text: IF YOU ARE USING ANY SERVICE AS AN EMPLOYEE, CONTRACTOR, OR AGENT OF A CORPORATION, PARTNERSHIP OR SIMILAR\n    ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY\nrestricted_uses:\n\
  - summary: Prohibited Customer Content\n  text: 'Customer Content may not: (i) be defamatory, harmful to minors, obscene, indecent, pornographic, libelous,\n    threatening, harassing, false, misleading or inaccurate'\n- summary: No health, financial or government ID data\n  text: (vi) contain any health, medical, financial, credit card or other payment information or any information\n    of any person or any government-issued identifying information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/securew2/eligibility/securew2-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from SecureW2's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Authentication
- PKI
- Certificates
- Network Security
- Passwordless
- RADIUS
- Identity
- MSP
---
