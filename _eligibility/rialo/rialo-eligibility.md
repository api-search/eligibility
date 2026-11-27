---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (iii) located outside of the U.S.; or (iv) otherwise blocked or denied under any OFAC sanctions program
  entity_types:
  - text: you are an individual, at least 18 years old and have capacity to enter into these Terms
    type: individual
  - text: if you use the Site on behalf of a corporation, legal entity or other organization, that you have full power and authority to do so
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No VPN to circumvent geo-blocking
    text: you will not use a virtual private network (“ VPN ”) or similar tool to circumvent any geo-blocking and/or other restrictions
  - summary: No use by sanctioned persons or in sanctioned countries
    text: if you are or are working on behalf of a Specially Designated National (“ SDN ”) or a person subject to similar blocking or denied party prohibitions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide information and/or documentation to verify or confirm your eligibility, including on a periodic or ongoing basis.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rialo
provenance_date: '2026-11-10'
provider_name: Rialo
provider_slug: rialo
slug: rialo-eligibility
source_date: '2026-11-10'
source_filename: rialo-eligibility.yml
source_heading: Eligibility
source_page: https://www.rialo.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rialo\naid: rialo\nurl: https://www.rialo.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (iii) located outside of the U.S.; or (iv) otherwise blocked or denied under any OFAC sanctions program\nentity_types:\n- type: individual\n  text: you are an individual, at least 18 years old and have capacity to enter into these Terms\n- type: business\n  text: if you use the Site on behalf of a corporation, legal entity or other organization, that you have full power\n    and authority to do so\nrestricted_uses:\n- summary: No VPN to circumvent geo-blocking\n  text: you\
  \ will not use a virtual private network (“ VPN ”) or similar tool to circumvent any geo-blocking and/or\n    other restrictions\n- summary: No use by sanctioned persons or in sanctioned countries\n  text: if you are or are working on behalf of a Specially Designated National (“ SDN ”) or a person subject to\n    similar blocking or denied party prohibitions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide information and/or documentation to verify or confirm your eligibility, including\n    on a periodic or ongoing basis.\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/rialo/eligibility/rialo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Rialo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Blockchain
- Layer 1
- Infrastructure
- DeFi
- Real World Assets
- Web3
- Privacy
---
