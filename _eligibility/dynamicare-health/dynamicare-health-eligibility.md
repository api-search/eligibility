---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering or using the Software on behalf of a company, healthcare institution or provider, or other organization, you represent that you have authority to enter into this Terms of Use
    type: business
  minimum_age:
    text: The Software is intended for persons thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Not for treatment, diagnosis or medical advice
    text: YOU AGREE THAT THE SOFTWARE IS NOT INTENDED TO BE USED FOR TREATMENT OF ANY MEDICAL CONDITION, MEDICAL EMERGENCIES, SELF-DIAGNOSIS OR MEDICAL ADVICE.
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
name: DynamiCare Health
provenance_date: '2026-11-09'
provider_name: DynamiCare Health
provider_slug: dynamicare-health
slug: dynamicare-health-eligibility
source_date: '2026-11-09'
source_filename: dynamicare-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.dynamicarehealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DynamiCare Health\naid: dynamicare-health\nurl: https://www.dynamicarehealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering or using the Software on behalf of a company, healthcare institution or provider,\n    or other organization, you represent that you have authority to enter into this Terms of Use\nrestricted_uses:\n- summary: Not for treatment, diagnosis or medical advice\n  text: YOU AGREE THAT THE SOFTWARE IS NOT INTENDED TO BE USED FOR TREATMENT OF ANY MEDICAL CONDITION, MEDICAL EMERGENCIES,\n\
  \    SELF-DIAGNOSIS OR MEDICAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Software is intended for persons thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/dynamicare-health/eligibility/dynamicare-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DynamiCare Health's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Digital Therapeutics
- SubstanceUseRecovery
- Health Tech
- Mental Health
---
