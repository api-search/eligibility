---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Certain features may be limited or unavailable in certain territories or to certain customers because of Trade Compliance Laws.
  entity_types:
  - text: 16.9 U.S. Government End Users. (a) Software and Documentation.
    type: government
  - text: For Consumers residing in Australia, as applicable, Our goods come with guarantees that cannot be excluded by the Australian Consumer Law.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Military, nuclear, medical, life-critical and critical infrastructure uses
    text: 'You shall not, directly or indirectly, use any of the Offerings for any of the following purposes: (a) military applications, nuclear power generation'
  - summary: Lethal autonomous weapons
    text: (d) the development, design, or operation of lethal autonomous weapons systems
  - source: https://liquidinstruments.com/terms/acceptable-use-policy/
    summary: Illegal or deceptive use
    text: Use the GenAI Features to perform any illegal, unlawful, fraudulent or deceptive activities
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
name: Liquid Instruments
provenance_date: '2026-11-09'
provider_name: Liquid Instruments
provider_slug: liquid-instruments
slug: liquid-instruments-eligibility
source_date: '2026-11-09'
source_filename: liquid-instruments-eligibility.yml
source_heading: Eligibility
source_page: https://liquidinstruments.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liquid Instruments\naid: liquid-instruments\nurl: https://liquidinstruments.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://liquidinstruments.com/terms-of-use/\n  - https://liquidinstruments.com/terms/acceptable-use-policy/\ncountries:\n  served: []\n  excluded: []\n  text: Certain features may be limited or unavailable in certain territories or to certain customers because of\n    Trade Compliance Laws.\nentity_types:\n- type: government\n  text: 16.9 U.S. Government End Users. (a) Software and Documentation.\n- type: individual\n  text: For Consumers residing in Australia,\
  \ as applicable, Our goods come with guarantees that cannot be excluded\n    by the Australian Consumer Law.\nrestricted_uses:\n- summary: Military, nuclear, medical, life-critical and critical infrastructure uses\n  text: 'You shall not, directly or indirectly, use any of the Offerings for any of the following purposes: (a)\n    military applications, nuclear power generation'\n- summary: Lethal autonomous weapons\n  text: (d) the development, design, or operation of lethal autonomous weapons systems\n- summary: Illegal or deceptive use\n  text: Use the GenAI Features to perform any illegal, unlawful, fraudulent or deceptive activities\n  source: https://liquidinstruments.com/terms/acceptable-use-policy/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/liquid-instruments/eligibility/liquid-instruments-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from Liquid Instruments's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Test and Measurement
- Instrumentation
- Hardware
- Oscilloscope
- Spectrum Analyzer
- Data Acquisition
- FPGA
- Photonics
- Scientific Instruments
- Electronics
- Laboratory
---
