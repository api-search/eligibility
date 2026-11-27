---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access to the Services from territories where the Content, or any part, is illegal is prohibited
  entity_types:
  - text: By using the Services, you represent and warrant that you are at least 18 years old and have the legal capacity to enter into a binding agreement.
    type: individual
  minimum_age:
    text: By using the Services, you represent and warrant that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Not for medical diagnosis or treatment
    text: No information contained on the Services is intended to be used for the purpose of medical diagnosis or treatment.
  - summary: CircHub research use only
    text: CGI RESULTS, CIRCHUB AND CIRCHUB OUTPUTS ARE FOR RESEARCH USE ONLY AND ARE NOT FOR USE IN DIAGNOSTIC PROCEDURES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: CircHub may be accessed only by authorized users under an account issued by Circular Genomics.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Circular Genomics
provenance_date: '2026-11-09'
provider_name: Circular Genomics
provider_slug: circular-genomics
slug: circular-genomics-eligibility
source_date: '2026-11-09'
source_filename: circular-genomics-eligibility.yml
source_heading: Eligibility
source_page: https://www.circulargenomics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Circular Genomics\naid: circular-genomics\nurl: https://www.circulargenomics.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access to the Services from territories where the Content, or any part, is illegal is prohibited\nentity_types:\n- type: individual\n  text: By using the Services, you represent and warrant that you are at least 18 years old and have the legal capacity\n    to enter into a binding agreement.\nrestricted_uses:\n- summary: Not for medical diagnosis or treatment\n  text: No information contained on the Services is intended to be used for the purpose\
  \ of medical diagnosis or\n    treatment.\n- summary: CircHub research use only\n  text: CGI RESULTS, CIRCHUB AND CIRCHUB OUTPUTS ARE FOR RESEARCH USE ONLY AND ARE NOT FOR USE IN DIAGNOSTIC PROCEDURES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: CircHub may be accessed only by authorized users under an account issued by Circular Genomics.\nminimum_age:\n  value: '18'\n  text: By using the Services, you represent and warrant that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/circular-genomics/eligibility/circular-genomics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Circular Genomics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Diagnostics
- Genomics
- Precision Medicine
- Neurology
- Life Sciences
- Health
- Clinical Laboratory
- Biomarkers
---
