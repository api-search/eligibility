---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms apply to you if you live in the United States or if you access our Services in the United States.
  entity_types:
  - text: You are not an insurance company or an employer
    type: business
  minimum_age:
    text: You are at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: Forensic genealogy
    text: You will not use the Services for any investigative forensic genealogy uses.
  - summary: Bone marrow or stem cell recipients
    text: The sample you provide is not from a bone marrow or stem cell recipient
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
name: 23andMe
provenance_date: '2026-11-09'
provider_name: 23andMe
provider_slug: 23andme
slug: 23andme-eligibility
source_date: '2026-11-09'
source_filename: 23andme-eligibility.yml
source_heading: Eligibility
source_page: https://www.23andme.org/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 23andMe\naid: 23andme\nurl: https://www.23andme.org/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms apply to you if you live in the United States or if you access our Services in the United States.\nentity_types:\n- type: business\n  text: You are not an insurance company or an employer\nrestricted_uses:\n- summary: Forensic genealogy\n  text: You will not use the Services for any investigative forensic genealogy uses.\n- summary: Bone marrow or stem cell recipients\n  text: The sample you provide is not from a bone marrow or stem cell recipient\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/23andme/eligibility/23andme-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from 23andMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Genetics
- Genomics
- DNA Testing
- Ancestry
- Consumer Health
- Bioinformatics
- Precision Medicine
- Pharmacogenomics
- Telehealth
- Health Research
---
