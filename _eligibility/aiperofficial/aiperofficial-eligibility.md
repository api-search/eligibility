---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are residing in the EU, ... Section 24 ... laws of Germany. The page does not list served or excluded countries.
  entity_types:
  - text: You may not use the Services and may not accept these Terms if (1) you are not of legal age to form a binding contract with Aiper
    type: individual
  minimum_age:
    text: OUR SERVICES ARE NOT INTENDED FOR USE OR ACCESS BY ANYONE UNDER THE AGE OF EIGHTEEN (18).
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
name: Aiper
provenance_date: '2026-11-09'
provider_name: Aiper
provider_slug: aiperofficial
slug: aiperofficial-eligibility
source_date: '2026-11-09'
source_filename: aiperofficial-eligibility.yml
source_heading: Eligibility
source_page: https://aiper.com/us/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aiper\naid: aiperofficial\nurl: https://aiper.com/us/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are residing in the EU, ... Section 24 ... laws of Germany. The page does not list served or excluded\n    countries.\nentity_types:\n- type: individual\n  text: You may not use the Services and may not accept these Terms if (1) you are not of legal age to form a binding\n    contract with Aiper\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: OUR SERVICES ARE NOT INTENDED\
  \ FOR USE OR ACCESS BY ANYONE UNDER THE AGE OF EIGHTEEN (18).\n"
source_yaml_url: https://artifacts.apis.io/aiperofficial/eligibility/aiperofficial-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Aiper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Robotics
- Consumer Electronics
- IoT
- Smart Home
- Home & Garden
- Hardware
- Artificial Intelligence
- Pool Care
---
