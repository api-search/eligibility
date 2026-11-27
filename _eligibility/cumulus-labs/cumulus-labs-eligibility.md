---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, or a resident or national of, any country subject to U.S. trade sanctions or embargoes
  entity_types:
  - text: You must be at least 18 years of age to access or use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to access or use the Service.
    value: '18'
  restricted_uses:
  - summary: Child sexual abuse material
    text: (a) Constitutes, depicts, promotes, or facilitates child sexual abuse material (CSAM) or the exploitation of minors in any form.
  - summary: Non-consensual intimate imagery
    text: (f) Generates or distributes non-consensual intimate imagery (NCII), including deepfake pornography of real persons.
  - summary: Weapons of mass destruction
    text: (g) Creates, distributes, or facilitates the creation of biological, chemical, nuclear, or radiological weapons or provides instructions for the same.
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
name: Cumulus Labs
provenance_date: '2026-11-09'
provider_name: Cumulus Labs
provider_slug: cumulus-labs
slug: cumulus-labs-eligibility
source_date: '2026-11-09'
source_filename: cumulus-labs-eligibility.yml
source_heading: Eligibility
source_page: https://cumuluslabs.io/terms-of-service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cumulus Labs\naid: cumulus-labs\nurl: https://cumuluslabs.io/terms-of-service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, or a resident or national of, any country subject\n    to U.S. trade sanctions or embargoes\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to access or use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have authority\n    to bind that organization to these Terms.\nrestricted_uses:\n\
  - summary: Child sexual abuse material\n  text: (a) Constitutes, depicts, promotes, or facilitates child sexual abuse material (CSAM) or the exploitation\n    of minors in any form.\n- summary: Non-consensual intimate imagery\n  text: (f) Generates or distributes non-consensual intimate imagery (NCII), including deepfake pornography of real\n    persons.\n- summary: Weapons of mass destruction\n  text: (g) Creates, distributes, or facilitates the creation of biological, chemical, nuclear, or radiological\n    weapons or provides instructions for the same.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to access or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cumulus-labs/eligibility/cumulus-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Cumulus Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Inference
- LLM
- AI Infrastructure
- GPU
- Machine Learning
- Model Serving
- Fine-Tuning
- API Gateway
- Y Combinator
---
