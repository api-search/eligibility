---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: NOT FOR USE OUTSIDE THE UNITED STATES OF AMERICA OHGI makes no claims that materials on the Platform or the App or any of the Services are appropriate or may be downloaded for use in locations outside the United States of America.
  entity_types:
  - text: You represent that you are (x) at least eighteen (18) years old; (y) of legal age to form a binding contract
    type: individual
  minimum_age:
    text: You represent that you are (x) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: No emergencies or suicidal crisis use
    text: DO NOT USE THIS SERVICE (i) IF YOU ARE EXPERIENCING A MEDICAL EMERGENCY; (ii) IF YOU ARE THINKING ABOUT SUICIDE
  - summary: No verifying provider credentials
    text: (p) use the Platform or any Service to verify the credentials of Providers.
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
name: Findoctave
provenance_date: '2026-11-09'
provider_name: Findoctave
provider_slug: findoctave
slug: findoctave-eligibility
source_date: '2026-11-09'
source_filename: findoctave-eligibility.yml
source_heading: Eligibility
source_page: https://www.findoctave.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Findoctave\naid: findoctave\nurl: https://www.findoctave.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: NOT FOR USE OUTSIDE THE UNITED STATES OF AMERICA OHGI makes no claims that materials on the Platform or\n    the App or any of the Services are appropriate or may be downloaded for use in locations outside the United\n    States of America.\nentity_types:\n- type: individual\n  text: You represent that you are (x) at least eighteen (18) years old; (y) of legal age to form a binding contract\nrestricted_uses:\n- summary: No emergencies or suicidal crisis use\n  text:\
  \ DO NOT USE THIS SERVICE (i) IF YOU ARE EXPERIENCING A MEDICAL EMERGENCY; (ii) IF YOU ARE THINKING ABOUT\n    SUICIDE\n- summary: No verifying provider credentials\n  text: (p) use the Platform or any Service to verify the credentials of Providers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (x) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/findoctave/eligibility/findoctave-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Findoctave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Healthcare
- Therapy
- Telehealth
- Behavioral Health
---
