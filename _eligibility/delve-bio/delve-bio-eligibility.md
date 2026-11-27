---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of your employer or another entity (referred to as “Company” and included in use of “you”), you represent and warrant that you are authorized to bind such employer or entity to these Terms
    type: business
  - text: 'To create a Personal Account, you will provide Delve Bio with the following information: your full legal name, email address, and any other requested information.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You represent, warrant and covenant that (a) you are not, and are not acting on behalf of, (a) any person who is a citizen, national, or resident of, or who is controlled by the government of any country to which the United States has prohibited export transactions
  - summary: Non-FDA-cleared use
    text: THE SAMPLE TRANSFER TUBES, ASSAYS AND REPORT HAVE NOT BEEN AND WILL NOT BE APPROVED, CLEARED, OR LICENSED BY THE UNITED STATES FOOD AND DRUG ADMINISTRATION
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once validated, Delve Bio will create your Company Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Delve Bio
provenance_date: '2026-11-09'
provider_name: Delve Bio
provider_slug: delve-bio
slug: delve-bio-eligibility
source_date: '2026-11-09'
source_filename: delve-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.delve.bio/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delve Bio\naid: delve-bio\nurl: https://www.delve.bio/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of your employer or another entity (referred to as “Company” and included in\n    use of “you”), you represent and warrant that you are authorized to bind such employer or entity to these Terms\n- type: individual\n  text: 'To create a Personal Account, you will provide Delve Bio with the following information: your full legal\n    name, email address, and any other requested information.'\nrestricted_uses:\n\
  - summary: Export and sanctions restrictions\n  text: You represent, warrant and covenant that (a) you are not, and are not acting on behalf of, (a) any person\n    who is a citizen, national, or resident of, or who is controlled by the government of any country to which the\n    United States has prohibited export transactions\n- summary: Non-FDA-cleared use\n  text: THE SAMPLE TRANSFER TUBES, ASSAYS AND REPORT HAVE NOT BEEN AND WILL NOT BE APPROVED, CLEARED, OR LICENSED\n    BY THE UNITED STATES FOOD AND DRUG ADMINISTRATION\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once validated, Delve Bio will create your Company Account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/delve-bio/eligibility/delve-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Delve Bio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Diagnostics
- Metagenomics
- Infectious Disease
- Genomics
- Next-Generation Sequencing
- Precision Medicine
- Clinical Laboratory
---
