---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: provides services to patients seeking treatment in hospitals, clinics, doctors or by other health service providers (together “Clinics”) around the world.
  entity_types:
  - text: by individuals (referred to below as "You", “Your” etc.)
    type: individual
  minimum_age:
    text: You must have full legal capacity and be at least 18 years old.
    value: '18'
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
name: Junomedical
provenance_date: '2026-11-09'
provider_name: Junomedical
provider_slug: junomedical
slug: junomedical-eligibility
source_date: '2026-11-09'
source_filename: junomedical-eligibility.yml
source_heading: Eligibility
source_page: https://www.qunomedical.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Junomedical\naid: junomedical\nurl: https://www.qunomedical.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: provides services to patients seeking treatment in hospitals, clinics, doctors or by other health service\n    providers (together “Clinics”) around the world.\nentity_types:\n- type: individual\n  text: by individuals (referred to below as \"You\", “Your” etc.)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must have full legal capacity and be at least\
  \ 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/junomedical/eligibility/junomedical-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Junomedical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Medical Travel
- Telehealth
- Patient Relationship Management
- Software-as-a-Service
---
