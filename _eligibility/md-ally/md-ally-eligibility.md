---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MD Ally Services, P.A. provides care to patients located in Florida, Colorado, and Arizona. MD Ally Services, P.C. provides care to patients located in California.
  entity_types:
  - text: You are at least 18 years old;
    type: individual
  - text: You have authority to accept these Terms for yourself and for any organization you represent;
    type: business
  - text: If you are a governmental entity, this section applies only to the extent the law governing you permits
    type: government
  minimum_age:
    text: You are at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: No PHI outside approved channels
    text: Do not submit protected health information through marketing sites, email, or any channel not approved for it.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If you use AllyNet, you are authorized to do so by a Partner.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Md Ally
provenance_date: '2026-11-10'
provider_name: Md Ally
provider_slug: md-ally
slug: md-ally-eligibility
source_date: '2026-11-10'
source_filename: md-ally-eligibility.yml
source_heading: Eligibility
source_page: https://www.mdally.com/privacy-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Md Ally\naid: md-ally\nurl: https://www.mdally.com/privacy-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MD Ally Services, P.A. provides care to patients located in Florida, Colorado, and Arizona. MD Ally Services,\n    P.C. provides care to patients located in California.\nentity_types:\n- type: individual\n  text: You are at least 18 years old;\n- type: business\n  text: You have authority to accept these Terms for yourself and for any organization you represent;\n- type: government\n  text: If you are a governmental entity, this section applies only to the extent the\
  \ law governing you permits\nrestricted_uses:\n- summary: No PHI outside approved channels\n  text: Do not submit protected health information through marketing sites, email, or any channel not approved for\n    it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: If you use AllyNet, you are authorized to do so by a Partner.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/md-ally/eligibility/md-ally-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Md Ally's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Digital Health
- Emergency Services
- Public Safety
- Compliance
---
