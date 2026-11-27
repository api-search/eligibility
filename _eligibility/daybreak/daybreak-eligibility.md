---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree and confirm that your use of the Platform, including the Provider Services, are for your own personal use only and that you are not using the Platform or the Provider Services for or behalf of any other person or organization.
    type: individual
  minimum_age:
    text: You hereby confirm that you are legally able to consent to receive Services, or have the consent of a parent or guardian, and that you are legally able to enter into a contract.
    value: null
  restricted_uses:
  - summary: Not for emergencies or suicidality
    text: THE PLATFORM IS NOT DESIGNED FOR USE IN ANY OF THE AFOREMENTIONED CASES AND THE PROVIDERS CANNOT PROVIDE THE ASSISTANCE REQUIRED IN ANY OF THE AFOREMENTIONED CASES.
  - summary: Not for official documentation
    text: YOU SHOULD NOT USE IT IF YOU NEED ANY OFFICIAL DOCUMENTATION OR APPROVALS FOR PURPOSES SUCH AS, BUT NOT LIMITED TO, COURT-ORDERED COUNSELING OR EMOTIONAL SERVICE DOG CERTIFICATION.
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
name: Daybreak
provenance_date: '2026-11-09'
provider_name: Daybreak
provider_slug: daybreak
slug: daybreak-eligibility
source_date: '2026-11-09'
source_filename: daybreak-eligibility.yml
source_heading: Eligibility
source_page: https://www.daybreakhealth.com/daybreak-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daybreak\naid: daybreak\nurl: https://www.daybreakhealth.com/daybreak-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You agree and confirm that your use of the Platform, including the Provider Services, are for your own personal\n    use only and that you are not using the Platform or the Provider Services for or behalf of any other person\n    or organization.\nrestricted_uses:\n- summary: Not for emergencies or suicidality\n  text: THE PLATFORM IS NOT DESIGNED FOR USE IN ANY OF THE AFOREMENTIONED CASES AND THE PROVIDERS\
  \ CANNOT PROVIDE\n    THE ASSISTANCE REQUIRED IN ANY OF THE AFOREMENTIONED CASES.\n- summary: Not for official documentation\n  text: YOU SHOULD NOT USE IT IF YOU NEED ANY OFFICIAL DOCUMENTATION OR APPROVALS FOR PURPOSES SUCH AS, BUT NOT\n    LIMITED TO, COURT-ORDERED COUNSELING OR EMOTIONAL SERVICE DOG CERTIFICATION.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You hereby confirm that you are legally able to consent to receive Services, or have the consent of a parent\n    or guardian, and that you are legally able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/daybreak/eligibility/daybreak-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Daybreak's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Healthcare
- Teletherapy
- Behavioral Health
- Education
- K-12
- Digital Health
---
