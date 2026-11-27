---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our Site is directed to people residing in the UK. We do not represent that content available on or through Our site is appropriate for use or available in other locations.
  entity_types:
  - text: Our Services are offered to healthcare professionals only, and are not made available to the general public.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Health practitioner use only
    text: Our Services are provided for health practitioner use, in the course of their employment only, and not for consumers or domestic use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By registering to use Our Services, you confirm that you are a healthcare professional working for a GP practice or other healthcare organisation that either has a licence with Us to use the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: C the Signs
provenance_date: '2026-11-09'
provider_name: C the Signs
provider_slug: cthesigns
slug: cthesigns-eligibility
source_date: '2026-11-09'
source_filename: cthesigns-eligibility.yml
source_heading: Eligibility
source_page: https://www.cthesigns.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: C the Signs\naid: cthesigns\nurl: https://www.cthesigns.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our Site is directed to people residing in the UK. We do not represent that content available on or through\n    Our site is appropriate for use or available in other locations.\nentity_types:\n- type: individual\n  text: Our Services are offered to healthcare professionals only, and are not made available to the general public.\nrestricted_uses:\n- summary: Health practitioner use only\n  text: Our Services are provided for health practitioner use, in the\
  \ course of their employment only, and not for\n    consumers or domestic use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By registering to use Our Services, you confirm that you are a healthcare professional working for a GP\n    practice or other healthcare organisation that either has a licence with Us to use the Service\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cthesigns/eligibility/cthesigns-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from C the Signs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Cancer Detection
- Clinical Decision Support
- Medical Devices
- Digital Health
- NHS
---
