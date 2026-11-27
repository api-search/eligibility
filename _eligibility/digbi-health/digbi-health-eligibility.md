---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: this Website and material provided on this Website are solely for promoting products, programs, and business operations within the United States.
  entity_types:
  - text: This Website is for use by users who are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: This Website is for use by users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: No medical advice or diagnosis
    text: THE WEBSITE DOES NOT OFFER MEDICAL ADVICE AND NOTHING CONTAINED IN THE CONTENT IS INTENDED TO CONSTITUTE PROFESSIONAL ADVICE FOR MEDICAL DIAGNOSIS OR TREATMENT
  - summary: Unlawful or export-restricted use
    text: Digbi Health prohibits your downloading or exporting of software or other material from this Website in violation of U.S. Export Laws and the laws of your resident country.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will be required to create a user account with Digbi Health
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Digbi Health
provenance_date: '2026-11-09'
provider_name: Digbi Health
provider_slug: digbi-health
slug: digbi-health-eligibility
source_date: '2026-11-09'
source_filename: digbi-health-eligibility.yml
source_heading: Eligibility
source_page: https://digbihealth.ai/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digbi Health\naid: digbi-health\nurl: https://digbihealth.ai/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: this Website and material provided on this Website are solely for promoting products, programs, and business\n    operations within the United States.\nentity_types:\n- type: individual\n  text: This Website is for use by users who are eighteen (18) years of age or older.\nrestricted_uses:\n- summary: No medical advice or diagnosis\n  text: THE WEBSITE DOES NOT OFFER MEDICAL ADVICE AND NOTHING CONTAINED IN THE CONTENT IS INTENDED TO CONSTITUTE\n\
  \    PROFESSIONAL ADVICE FOR MEDICAL DIAGNOSIS OR TREATMENT\n- summary: Unlawful or export-restricted use\n  text: Digbi Health prohibits your downloading or exporting of software or other material from this Website in\n    violation of U.S. Export Laws and the laws of your resident country.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will be required to create a user account with Digbi Health\nminimum_age:\n  value: '18'\n  text: This Website is for use by users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/digbi-health/eligibility/digbi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Digbi Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Digital Therapeutics
- Precision Medicine
- Genomics
- Microbiome
- Nutrition
- Chronic Care
- Telehealth
---
