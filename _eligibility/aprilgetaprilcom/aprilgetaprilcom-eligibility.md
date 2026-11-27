---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only use april if you are a tax filer in the United States who does not reside in the European Union.
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  - text: In the event that you choose to file a federal and/or state tax return on behalf of a business entity, you agree that you are an authorized representative of the business entity-taxpayer
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission
    value: null
  restricted_uses:
  - summary: Tax filing outside scope
    text: april does not currently support the Services in all jurisdictions and does not support all tax situations, including but not limited to users in certain states.
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
name: Aprilgetaprilcom
provenance_date: '2026-11-09'
provider_name: Aprilgetaprilcom
provider_slug: aprilgetaprilcom
slug: aprilgetaprilcom-eligibility
source_date: '2026-11-09'
source_filename: aprilgetaprilcom-eligibility.yml
source_heading: Eligibility
source_page: https://getapril.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aprilgetaprilcom\naid: aprilgetaprilcom\nurl: https://getapril.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only use april if you are a tax filer in the United States who does not reside in the European Union.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n- type: business\n  text: In the event that you choose to file a federal and/or state tax return\
  \ on behalf of a business entity, you\n    agree that you are an authorized representative of the business entity-taxpayer\nrestricted_uses:\n- summary: Tax filing outside scope\n  text: april does not currently support the Services in all jurisdictions and does not support all tax situations,\n    including but not limited to users in certain states.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission\n"
source_yaml_url: https://artifacts.apis.io/aprilgetaprilcom/eligibility/aprilgetaprilcom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Aprilgetaprilcom's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Tax
- Embedded
---
