---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Service for use only by persons located in the United States.
  entity_types:
  - text: Your access to and use of this Online Service Platform is strictly contingent upon your being at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: Your access to and use of this Online Service Platform is strictly contingent upon your being at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis or treatment
    text: the Services are not intended for the diagnosis of diseases or other conditions, the cure, mitigation, treatment, or prevention of diseases
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
name: Hello Pediatrics
provenance_date: '2026-11-09'
provider_name: Hello Pediatrics
provider_slug: hello-pediatrics
slug: hello-pediatrics-eligibility
source_date: '2026-11-09'
source_filename: hello-pediatrics-eligibility.yml
source_heading: Eligibility
source_page: https://hellopediatrics.com/terms-of-use-1418/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hello Pediatrics\naid: hello-pediatrics\nurl: https://hellopediatrics.com/terms-of-use-1418/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Service for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: Your access to and use of this Online Service Platform is strictly contingent upon your being at least eighteen\n    (18) years of age.\nrestricted_uses:\n- summary: Not for diagnosis or treatment\n  text: the Services are not intended for the diagnosis of diseases or other conditions, the cure, mitigation, treatment,\n\
  \    or prevention of diseases\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Your access to and use of this Online Service Platform is strictly contingent upon your being at least eighteen\n    (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/hello-pediatrics/eligibility/hello-pediatrics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hello Pediatrics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Pediatrics
- Virtual Care
- Digital Health
- Medical Practice
---
