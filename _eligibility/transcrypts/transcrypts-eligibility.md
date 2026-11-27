---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be appropriate or available for use in some non-U.S. jurisdictions.
  entity_types:
  - text: If you are an End User or other individual, the arbitration will be administered by the American Arbitration Association under its Consumer Arbitration Rules
    type: individual
  - text: If you are a Verifier or other organization, the arbitration will be administered by the American Arbitration Association under its Commercial Arbitration Rules
    type: business
  minimum_age:
    text: if you are under the age of majority in your territory, in no case are you permitted to register with Transcrypts or provide your personal information to Transcrypts.
    value: age of majority in your territory
  restricted_uses:
  - summary: Consumer reports
    text: Transcrypts is not a Consumer Reporting Agency, and Transcrypts does not produce consumer reports, as those terms are defined by the Fair Credit Reporting Act.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For clarity, Transcrypts may, but is under is under no obligation to, confirm the actual identity or authority of any End User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TransCrypts
provenance_date: '2026-11-10'
provider_name: TransCrypts
provider_slug: transcrypts
slug: transcrypts-eligibility
source_date: '2026-11-10'
source_filename: transcrypts-eligibility.yml
source_heading: Eligibility
source_page: https://www.transcrypts.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TransCrypts\naid: transcrypts\nurl: https://www.transcrypts.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be appropriate or available for use in some non-U.S. jurisdictions.\nentity_types:\n- type: individual\n  text: If you are an End User or other individual, the arbitration will be administered by the American Arbitration\n    Association under its Consumer Arbitration Rules\n- type: business\n  text: If you are a Verifier or other organization, the arbitration will be administered by the American Arbitration\n    Association under its\
  \ Commercial Arbitration Rules\nrestricted_uses:\n- summary: Consumer reports\n  text: Transcrypts is not a Consumer Reporting Agency, and Transcrypts does not produce consumer reports, as those\n    terms are defined by the Fair Credit Reporting Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: For clarity, Transcrypts may, but is under is under no obligation to, confirm the actual identity or authority\n    of any End User.\nminimum_age:\n  value: age of majority in your territory\n  text: if you are under the age of majority in your territory, in no case are you permitted to register with Transcrypts\n    or provide your personal information to Transcrypts.\n"
source_yaml_url: https://artifacts.apis.io/transcrypts/eligibility/transcrypts-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from TransCrypts's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Blockchain
- Identity
- Verification
- Credentials
- Background Checks
- Employment Verification
- Self-Sovereign Data
- HIPAA
---
