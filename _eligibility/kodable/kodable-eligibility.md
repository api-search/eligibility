---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website and the Platform are based in the United States. We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: The Platform is available only for individuals aged 18 years or older.
    type: individual
  - text: Customers with unique organizational structures (including non-school organizations) or special circumstances that may affect licensing requirements are encouraged to contact Kodable for clarification.
    type: other
  minimum_age:
    text: The Platform is available only for individuals aged 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Subscription license site restriction
    text: Each Subscription License is specific to the physical campus or site for which it was purchased and may not be shared or transferred between campuses, sites, or settings without prior written consent from Kodable.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Kodable is under no obligation to accept any individual as a Teacher or Parent, and may accept or reject any registration in its sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kodable
provenance_date: '2026-11-09'
provider_name: Kodable
provider_slug: kodable
slug: kodable-eligibility
source_date: '2026-11-09'
source_filename: kodable-eligibility.yml
source_heading: Eligibility
source_page: https://resources.kodable.com/KodableTOS.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kodable\naid: kodable\nurl: https://resources.kodable.com/KodableTOS.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website and the Platform are based in the United States. We make no claims concerning whether the Content\n    may be downloaded, viewed, or be appropriate for use outside of the United States.\nentity_types:\n- type: individual\n  text: The Platform is available only for individuals aged 18 years or older.\n- type: other\n  text: Customers with unique organizational structures (including non-school organizations) or special circumstances\n    that may affect\
  \ licensing requirements are encouraged to contact Kodable for clarification.\nrestricted_uses:\n- summary: Subscription license site restriction\n  text: Each Subscription License is specific to the physical campus or site for which it was purchased and may\n    not be shared or transferred between campuses, sites, or settings without prior written consent from Kodable.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Kodable is under no obligation to accept any individual as a Teacher or Parent, and may accept or reject\n    any registration in its sole and complete discretion.\nminimum_age:\n  value: '18'\n  text: The Platform is available only for individuals aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/kodable/eligibility/kodable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Kodable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- Learning
- Coding Education
- Computer Science
- Games
- Children
---
