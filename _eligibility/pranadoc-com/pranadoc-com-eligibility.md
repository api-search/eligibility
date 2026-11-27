---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are primarily designed and intended for use by individuals located in the United States.
  entity_types:
  - text: You represent and warrant that you are at least eighteen years of age and have the legal capacity to enter into these Terms.
    type: individual
  - text: either an individual or the entity you represent
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen years of age and have the legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Medical or psychiatric emergencies
    text: Use or rely on the Services in relation to any medical or psychiatric emergency, or any situation that feels life-threatening, rapidly worsening, or time-critical.
  - summary: Reverse engineering and copying
    text: Reverse compile, disassemble, decompile or engineer, copy, modify or adapt the whole or any part of the Services
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
name: Prana Health
provenance_date: '2026-11-10'
provider_name: Prana Health
provider_slug: pranadoc-com
slug: pranadoc-com-eligibility
source_date: '2026-11-10'
source_filename: pranadoc-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.pranadoc.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prana Health\naid: pranadoc-com\nurl: https://www.pranadoc.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are primarily designed and intended for use by individuals located in the United States.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least eighteen years of age and have the legal capacity to enter\n    into these Terms.\n- type: business\n  text: either an individual or the entity you represent\nrestricted_uses:\n- summary: Medical or psychiatric emergencies\n  text: Use or rely on the Services in relation\
  \ to any medical or psychiatric emergency, or any situation that feels\n    life-threatening, rapidly worsening, or time-critical.\n- summary: Reverse engineering and copying\n  text: Reverse compile, disassemble, decompile or engineer, copy, modify or adapt the whole or any part of the\n    Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen years of age and have the legal capacity to enter\n    into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/pranadoc-com/eligibility/pranadoc-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Prana Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
