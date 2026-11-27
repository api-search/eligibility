---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  entity_types:
  - text: If you are under 18 years old, you may use the Services only with the approval of your parent or guardian, with the exception of Atlas which is not available to users under 18 years of age.
    type: individual
  minimum_age:
    text: If you are under 18 years old, you may use the Services only with the approval of your parent or guardian, with the exception of Atlas which is not available to users under 18 years of age.
    value: 18 (Atlas only); parental approval below 18 for other Services
  restricted_uses:
  - summary: Not a medical service
    text: The Services are not designed to diagnose, treat, mitigate or cure any disease, physical or mental health condition and are not a substitute for medical advice
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
name: Elevate
provenance_date: '2026-11-09'
provider_name: Elevate
provider_slug: elevateapp-com
slug: elevateapp-com-eligibility
source_date: '2026-11-09'
source_filename: elevateapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://themindcompany.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elevate\naid: elevateapp-com\nurl: https://themindcompany.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country that is subject to a U.S. Government embargo, or that\n    has been designated by the U.S. Government as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: If you are under 18 years old, you may use the Services only with the approval of your parent or guardian,\n    with the exception of Atlas which is not available to users under 18 years of age.\nrestricted_uses:\n\
  - summary: Not a medical service\n  text: The Services are not designed to diagnose, treat, mitigate or cure any disease, physical or mental health\n    condition and are not a substitute for medical advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 (Atlas only); parental approval below 18 for other Services\n  text: If you are under 18 years old, you may use the Services only with the approval of your parent or guardian,\n    with the exception of Atlas which is not available to users under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/elevateapp-com/eligibility/elevateapp-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Elevate's own page on 2026-11-09.
synthetic: false
tags:
- Brain Training
- Mobile App
- Health
- Education
- Cognitive Science
---
