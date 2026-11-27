---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (a) Moster resides in the United States
  entity_types:
  - text: REFERS TO THE INDIVIDUAL USER IDENTIFIED WITH A MOS USER ACCOUNT
    type: individual
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH MOS OR ARE USING THE SERVICES UNDER THE SUPERVISION OF A PARENT OR GUARDIAN
    value: legal age or parental supervision
  restricted_uses:
  - summary: Not financial advice
    text: OUR ADVISORS ARE NOT LICENSED FINANCIAL ADVISORS.
  - summary: Informational use only
    text: THE SCHOLARSHIP AND ADVISOR SERVICES ARE INTENDED TO BE USED FOR INFORMATIONAL PURPOSES ONLY.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: is a student and gets verified by Mos
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mos
provenance_date: '2026-11-10'
provider_name: Mos
provider_slug: mos
slug: mos-eligibility
source_date: '2026-11-10'
source_filename: mos-eligibility.yml
source_heading: Eligibility
source_page: https://mos.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mos\naid: mos\nurl: https://mos.com/service-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (a) Moster resides in the United States\nentity_types:\n- type: individual\n  text: REFERS TO THE INDIVIDUAL USER IDENTIFIED WITH A MOS USER ACCOUNT\nrestricted_uses:\n- summary: Not financial advice\n  text: OUR ADVISORS ARE NOT LICENSED FINANCIAL ADVISORS.\n- summary: Informational use only\n  text: THE SCHOLARSHIP AND ADVISOR SERVICES ARE INTENDED TO BE USED FOR INFORMATIONAL PURPOSES ONLY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: is a student\
  \ and gets verified by Mos\nminimum_age:\n  value: legal age or parental supervision\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH MOS OR ARE USING THE SERVICES UNDER THE SUPERVISION\n    OF A PARENT OR GUARDIAN\n"
source_yaml_url: https://artifacts.apis.io/mos/eligibility/mos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mos's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Higher Education
- Financial Aid
- Scholarships
- Student Finance
- Fintech
- Consumer Finance
---
