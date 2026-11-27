---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: YOU HEREBY WARRANT THAT (I) YOU ARE NOT LOCATED IN A COUNTRY THAT IS SUBJECT TO A US OR EU GOVERNMENT EMBARGO
  entity_types:
  - text: If you are the US Federal Government (Government) Executive Agency
    type: government
  minimum_age:
    text: You further represent and warrant that you are over the age of 18, or the legal age of majority in your jurisdiction of residence.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use and access the Service, directly or indirectly, only for lawful, authorized purposes
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
name: Favro
provenance_date: '2026-11-09'
provider_name: Favro
provider_slug: favro
slug: favro-eligibility
source_date: '2026-11-09'
source_filename: favro-eligibility.yml
source_heading: Eligibility
source_page: https://help.favro.com/en/articles/1024895-favro-s-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Favro\naid: favro\nurl: https://help.favro.com/en/articles/1024895-favro-s-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: YOU HEREBY WARRANT THAT (I) YOU ARE NOT LOCATED IN A COUNTRY THAT IS SUBJECT TO A US OR EU GOVERNMENT EMBARGO\nentity_types:\n- type: government\n  text: If you are the US Federal Government (Government) Executive Agency\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use and access the Service, directly or indirectly, only for lawful, authorized purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You further represent and warrant that you are over the age of 18, or the legal age of majority in your\n    jurisdiction of residence.\n"
source_yaml_url: https://artifacts.apis.io/favro/eligibility/favro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Favro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Project Management
- Collaboration
- Agile
- Planning
- Task Management
- Kanban
- Productivity
---
