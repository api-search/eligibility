---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - SD
    served: []
    text: (i) an embargoed/terrorist supporting country, including Cuba, Iran, North Korea, Syria, Sudan
  entity_types:
  - text: You must be at least 18 years old to make purchases from SLG.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Own use only, no resale
    text: You represent that each Product you purchase is for your own use and not for resale.
  - summary: No medical advice via AI features
    text: To provide medical advice and medical results interpretation
  - summary: No inappropriate AI images
    text: To create inappropriate images, including those that are violent, explicit, shocking, or offensive.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- SD
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Glowforge
provenance_date: '2026-11-09'
provider_name: Glowforge
provider_slug: glowforge
slug: glowforge-eligibility
source_date: '2026-11-09'
source_filename: glowforge-eligibility.yml
source_heading: Eligibility
source_page: https://glowforge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glowforge\naid: glowforge\nurl: https://glowforge.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - SD\n  text: (i) an embargoed/terrorist supporting country, including Cuba, Iran, North Korea, Syria, Sudan\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to make purchases from SLG.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n\
  - summary: Own use only, no resale\n  text: You represent that each Product you purchase is for your own use and not for resale.\n- summary: No medical advice via AI features\n  text: To provide medical advice and medical results interpretation\n- summary: No inappropriate AI images\n  text: To create inappropriate images, including those that are violent, explicit, shocking, or offensive.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/glowforge/eligibility/glowforge-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Glowforge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hardware
- Laser Cutting
- 3D Printing
- Manufacturing
- Maker
- Consumer Electronics
- IoT
---
