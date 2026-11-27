---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Service from jurisdictions where the contents of the Service are illegal or penalized is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not a doctor-patient relationship
    text: By accepting these Terms of Use, you acknowledge and agree that Equip is not a healthcare provider and that by using the Service, you are not entering into a doctor-patient or other health care provider-patient relationship with Equip.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We may ask you for identification or other information to verify your age and identity. We reserve the right to refuse to provide Services and/or access to the Platform to you if you are unwilling to provide such identification or information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Equip Health
provenance_date: '2026-11-09'
provider_name: Equip Health
provider_slug: equip-health
slug: equip-health-eligibility
source_date: '2026-11-09'
source_filename: equip-health-eligibility.yml
source_heading: Eligibility
source_page: https://equip.health/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Equip Health\naid: equip-health\nurl: https://equip.health/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Service from jurisdictions where the contents of the Service are illegal or penalized is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Not a doctor-patient relationship\n  text: By accepting these Terms of Use, you acknowledge and agree that Equip is not a healthcare provider and that\n    by using the Service, you are not entering into a doctor-patient or other health care provider-patient relationship\n    with Equip.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: false\n  text: We may ask you for identification or other information to verify your age and identity. We reserve the right\n    to refuse to provide Services and/or access to the Platform to you if you are unwilling to provide such identification\n    or information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/equip-health/eligibility/equip-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Equip Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Telehealth
- Mental Health
- Eating Disorder Treatment
- Virtual Care
- Health Insurance
---
