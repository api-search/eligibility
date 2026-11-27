---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A license is granted to a single legal entity ("Licensee"), and is authorized for use solely with that entity.
    type: business
  minimum_age:
    text: you agree that you are of legal age
    value: legal age
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
name: AnnounceKit
provenance_date: '2026-11-09'
provider_name: AnnounceKit
provider_slug: announcekit
slug: announcekit-eligibility
source_date: '2026-11-09'
source_filename: announcekit-eligibility.yml
source_heading: Eligibility
source_page: https://announcekit.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnnounceKit\naid: announcekit\nurl: https://announcekit.app/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A license is granted to a single legal entity (\"Licensee\"), and is authorized for use solely with that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you agree that you are of legal age\n"
source_yaml_url: https://artifacts.apis.io/announcekit/eligibility/announcekit-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AnnounceKit's own page on 2026-11-09.
synthetic: false
tags:
- Changelog
- Feature Requests
- NPS
- Notification
- Product Communication
- Roadmaps
- Software-as-a-Service
- Widgets
---
