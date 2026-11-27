---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is hosted in the United States of America and is intended for use by residents of the United States of America only.
  entity_types:
  - text: By accepting these Terms of Use, you represent and warrant that you are 18 years of age or older
    type: individual
  - text: if you have accepted these Terms of Use on behalf of any business (such as a corporation, partnership, limited liability company, or other organization) or other entity, you represent and warrant that you have legal authority to do so.
    type: business
  minimum_age:
    text: By accepting these Terms of Use, you represent and warrant that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Medical information not a substitute for advice
    text: THE CONTENT OF THE SITE IS NOT INTENDED IN ANY WAY TO SUBSTITUTE FOR PROFESSIONAL MEDICAL ADVICE AND SHOULD NOT BE RELIED ON FOR MEDICAL DIAGNOSIS OR TREATMENT.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some areas of the Site may require registration. Each registration is for a single user only.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Initial Therapeutics
provenance_date: '2026-11-09'
provider_name: Initial Therapeutics
provider_slug: initial-therapeutics
slug: initial-therapeutics-eligibility
source_date: '2026-11-09'
source_filename: initial-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://initialtx.com/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Initial Therapeutics\naid: initial-therapeutics\nurl: https://initialtx.com/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is hosted in the United States of America and is intended for use by residents of the United States\n    of America only.\nentity_types:\n- type: individual\n  text: By accepting these Terms of Use, you represent and warrant that you are 18 years of age or older\n- type: business\n  text: if you have accepted these Terms of Use on behalf of any business (such as a corporation, partnership, limited\n    liability company, or other\
  \ organization) or other entity, you represent and warrant that you have legal authority\n    to do so.\nrestricted_uses:\n- summary: Medical information not a substitute for advice\n  text: THE CONTENT OF THE SITE IS NOT INTENDED IN ANY WAY TO SUBSTITUTE FOR PROFESSIONAL MEDICAL ADVICE AND SHOULD\n    NOT BE RELIED ON FOR MEDICAL DIAGNOSIS OR TREATMENT.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some areas of the Site may require registration. Each registration is for a single user only.\nminimum_age:\n  value: '18'\n  text: By accepting these Terms of Use, you represent and warrant that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/initial-therapeutics/eligibility/initial-therapeutics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Initial Therapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Therapeutics
- Drug Discovery
- Small Molecule
- Oncology
- Life Sciences
- Preclinical
---
