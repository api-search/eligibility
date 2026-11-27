---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to individuals and organizations that create, access, or use the Service.
    type: individual
  - text: Forged VMS is offered to commercial venue operators through a demo and direct sales process.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: complete any required verification steps before using restricted features
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Forged Sports
provenance_date: '2026-11-09'
provider_name: Forged Sports
provider_slug: forged-sports-inc
slug: forged-sports-inc-eligibility
source_date: '2026-11-09'
source_filename: forged-sports-inc-eligibility.yml
source_heading: Eligibility
source_page: https://forgedsports.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forged Sports\naid: forged-sports-inc\nurl: https://forgedsports.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms apply to individuals and organizations that create, access, or use the Service.\n- type: business\n  text: Forged VMS is offered to commercial venue operators through a demo and direct sales process.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: complete any required verification steps before using restricted features\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/forged-sports-inc/eligibility/forged-sports-inc-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Forged Sports's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Golf
- Sports
- Venue Management
- Business Intelligence
- Booking
- Analytics
- Software-as-a-Service
---
