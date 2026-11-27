---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  minimum_age:
    text: represent that you are at least 18 years old and reside in the United States or its territories
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited conduct
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: AdvisorFinder does not verify investment advisor compliance with applicable regulations and makes no representations regarding advisor regulatory status, qualifications, or compliance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AdvisorFinder
provenance_date: '2026-11-09'
provider_name: AdvisorFinder
provider_slug: advisorfinder-com
slug: advisorfinder-com-eligibility
source_date: '2026-11-09'
source_filename: advisorfinder-com-eligibility.yml
source_heading: Eligibility
source_page: https://advisorfinder.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdvisorFinder\naid: advisorfinder-com\nurl: https://advisorfinder.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited conduct\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: AdvisorFinder does not verify investment advisor compliance with applicable regulations and makes no representations\n\
  \    regarding advisor regulatory status, qualifications, or compliance.\nminimum_age:\n  value: '18'\n  text: represent that you are at least 18 years old and reside in the United States or its territories\n"
source_yaml_url: https://artifacts.apis.io/advisorfinder-com/eligibility/advisorfinder-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AdvisorFinder's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Advisor
- Fintech
- Marketplace
- Free
---
