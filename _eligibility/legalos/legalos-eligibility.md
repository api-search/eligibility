---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you represent and warrant that (i) you have full legal authority to bind your employer
    type: business
  minimum_age:
    text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Impersonation and false information
    text: (xix) submitting false, fraudulent or misleading information in visa application
  - summary: Preparing petitions for third parties without authorization
    text: (xx) using the Services to prepare immigration petitions for third parties without authorization
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
name: LegalOS
provenance_date: '2026-11-09'
provider_name: LegalOS
provider_slug: legalos
slug: legalos-eligibility
source_date: '2026-11-09'
source_filename: legalos-eligibility.yml
source_heading: Eligibility
source_page: https://www.legalos.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LegalOS\naid: legalos\nurl: https://www.legalos.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you\n    represent and warrant that (i) you have full legal authority to bind your employer\nrestricted_uses:\n- summary: Impersonation and false information\n  text: (xix) submitting false, fraudulent or misleading information in visa application\n- summary: Preparing petitions for third parties without authorization\n\
  \  text: (xx) using the Services to prepare immigration petitions for third parties without authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which\n    you reside\n"
source_yaml_url: https://artifacts.apis.io/legalos/eligibility/legalos-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LegalOS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Immigration
- Artificial Intelligence
- Professional Services
- Visa
- Compliance
---
