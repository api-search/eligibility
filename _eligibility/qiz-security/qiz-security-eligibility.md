---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that it is not located in, and is not a national or resident of, any country subject to comprehensive U.S. or EU trade sanctions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or surveillance use
    text: Use the Software in violation of applicable law, or to build or support surveillance, data exfiltration, or other tooling adverse to the security of any third party's systems.
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
name: Qiz Security
provenance_date: '2026-11-10'
provider_name: Qiz Security
provider_slug: qiz-security
slug: qiz-security-eligibility
source_date: '2026-11-10'
source_filename: qiz-security-eligibility.yml
source_heading: Eligibility
source_page: https://qizsecurity.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qiz Security\naid: qiz-security\nurl: https://qizsecurity.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that it is not located in, and is not a national or resident of, any country subject\n    to comprehensive U.S. or EU trade sanctions\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or surveillance use\n  text: Use the Software in violation of applicable law, or to build or support surveillance, data exfiltration,\n    or other tooling adverse to the security of any third party's systems.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qiz-security/eligibility/qiz-security-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Qiz Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Cryptography
- Post-Quantum Cryptography
- Quantum-Safe
- Cryptographic Discovery
- Compliance
- Security
---
