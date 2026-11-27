---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any person accessing DroneShield Group Pty Ltd’s (ABN 44 668 560 610)(“DroneShield”) locations and/or systems
    type: individual
  - text: If a Visitor’s access to a DroneShield Location and ongoing related interactions with DroneShield staff arise from them being an independent contractor to DroneShield
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: (d) not export, re-export, broker, divert or transfer, directly or indirectly, any Export Controlled Items in violation of any then current export control laws, regulations and orders
  - summary: No use of Confidential Information for LLMs
    text: (e) not provide any Confidential Information to any Large Language Model, nor use any Confidential Information to train any Large Language Model
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Prior to accessing any DroneShield Location, Visitors must upload a copy of all passports they currently hold
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DroneShield
provenance_date: '2026-11-09'
provider_name: DroneShield
provider_slug: droneshield
slug: droneshield-eligibility
source_date: '2026-11-09'
source_filename: droneshield-eligibility.yml
source_heading: Eligibility
source_page: https://www.droneshield.com/terms-of-access
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DroneShield\naid: droneshield\nurl: https://www.droneshield.com/terms-of-access\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any person accessing DroneShield Group Pty Ltd’s (ABN 44 668 560 610)(“DroneShield”) locations and/or systems\n- type: business\n  text: If a Visitor’s access to a DroneShield Location and ongoing related interactions with DroneShield staff\n    arise from them being an independent contractor to DroneShield\nrestricted_uses:\n- summary: Export control compliance\n  text: (d) not export, re-export, broker,\
  \ divert or transfer, directly or indirectly, any Export Controlled Items\n    in violation of any then current export control laws, regulations and orders\n- summary: No use of Confidential Information for LLMs\n  text: (e) not provide any Confidential Information to any Large Language Model, nor use any Confidential Information\n    to train any Large Language Model\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Prior to accessing any DroneShield Location, Visitors must upload a copy of all passports they currently\n    hold\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/droneshield/eligibility/droneshield-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from DroneShield's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Counter-Drone
- Defense
- Drones
- Artificial Intelligence
- Security
- ASX Listed
---
