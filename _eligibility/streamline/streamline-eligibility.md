---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms are applicable to Users located in the United States only.
  entity_types:
  - text: To use the Service and Sites you must be, and represent and warrant that you are, at least 13 years of age and competent to agree to these Terms.
    type: individual
  - text: the organization (e.g., your employer or another entity or person, called the “Customer”) that entered into a separate agreement that governs delivery, access, and use of the Service
    type: business
  minimum_age:
    text: at least 13 years of age and competent to agree to these Terms
    value: '13'
  restricted_uses:
  - summary: Unlawful or fraudulent activity
    text: 'You may not utilize the Service and Sites to carry out, promote or support: any unlawful or fraudulent activities'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may require you to provide information that may be used to confirm your identity and help ensure the security of your account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Streamline
provenance_date: '2026-11-10'
provider_name: Streamline
provider_slug: streamline
slug: streamline-eligibility
source_date: '2026-11-10'
source_filename: streamline-eligibility.yml
source_heading: Eligibility
source_page: https://www.streamline.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Streamline\naid: streamline\nurl: https://www.streamline.ai/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms are applicable to Users located in the United States only.\nentity_types:\n- type: individual\n  text: To use the Service and Sites you must be, and represent and warrant that you are, at least 13 years of age\n    and competent to agree to these Terms.\n- type: business\n  text: the organization (e.g., your employer or another entity or person, called the “Customer”) that entered into\n    a separate agreement that governs delivery, access,\
  \ and use of the Service\nrestricted_uses:\n- summary: Unlawful or fraudulent activity\n  text: 'You may not utilize the Service and Sites to carry out, promote or support: any unlawful or fraudulent\n    activities'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may require you to provide information that may be used to confirm your identity and help ensure the\n    security of your account\nminimum_age:\n  value: '13'\n  text: at least 13 years of age and competent to agree to these Terms\n"
source_yaml_url: https://artifacts.apis.io/streamline/eligibility/streamline-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Streamline's own page on 2026-11-10.
synthetic: false
tags:
- Legal Tech
- Automation
- Artificial Intelligence
- Workflows
- Document Generation
---
