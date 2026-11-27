---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - EU
    - EEA
    served:
    - US
    text: The Site and App are intended for users situated in the United States. We currently do not offer goods and services to the EU or EEA.
  minimum_age:
    text: You must be 18 years old in order to make a purchase on our Site and the App.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You may use the Site and the App only for your own noncommercial personal use and in compliance with these Terms.
  - summary: No drop shipping
    text: Using the Site or the App to drop ship merchandise to third parties.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.
excluded_countries:
- EU
- EEA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: birchbox
provenance_date: '2026-11-09'
provider_name: birchbox
provider_slug: birchbox
slug: birchbox-eligibility
source_date: '2026-11-09'
source_filename: birchbox-eligibility.yml
source_heading: Eligibility
source_page: https://www.birchbox.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: birchbox\naid: birchbox\nurl: https://www.birchbox.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - EU\n  - EEA\n  text: The Site and App are intended for users situated in the United States. We currently do not offer goods and\n    services to the EU or EEA.\nentity_types: []\nrestricted_uses:\n- summary: No commercial use\n  text: You may use the Site and the App only for your own noncommercial personal use and in compliance with these\n    Terms.\n- summary: No drop shipping\n  text: Using the Site or the App to drop ship merchandise to third parties.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.\nminimum_age:\n  value: '18'\n  text: You must be 18 years old in order to make a purchase on our Site and the App.\n"
source_yaml_url: https://artifacts.apis.io/birchbox/eligibility/birchbox-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from birchbox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beauty
- Subscription
- E-Commerce
- Retail
- Consumer
- Cosmetics
---
