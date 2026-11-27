---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only use the GlossGenius Services and your Account for business purposes in the fifty states of the United States of America, its territories, and the District of Columbia.
  entity_types:
  - text: You confirm upon creating an Account that you are 18 years of age or older and either a legal resident of the United States, a United States citizen or a business entity authorized to do business by the states in which you operate.
    type: business
  - text: You must be an authorized representative of the business you represent on the GlossGenius Services.
    type: individual
  minimum_age:
    text: You represent and warrant that you are 18 years of age or older and have the legal right and capacity to enter into these Terms of Service in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: No personal or consumer use
    text: Personal, consumer or family use of a Subscription is not intended or permitted.
  - summary: No health-related use without HIPAA steps
    text: Unless and until you have completed these steps, you shall not use GlossGenius’ services for any health-related purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You further authorize GlossGenius and/or its payment processing partners to perform identity verification and to obtain credit reports or run other background inquiries to assess a Professional’s eligibility to continue using the GlossGenius Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GlossGenius
provenance_date: '2026-11-09'
provider_name: GlossGenius
provider_slug: glossgenius
slug: glossgenius-eligibility
source_date: '2026-11-09'
source_filename: glossgenius-eligibility.yml
source_heading: Eligibility
source_page: https://glossgenius.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GlossGenius\naid: glossgenius\nurl: https://glossgenius.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only use the GlossGenius Services and your Account for business purposes in the fifty states of\n    the United States of America, its territories, and the District of Columbia.\nentity_types:\n- type: business\n  text: You confirm upon creating an Account that you are 18 years of age or older and either a legal resident of\n    the United States, a United States citizen or a business entity authorized to do business by the states\
  \ in which\n    you operate.\n- type: individual\n  text: You must be an authorized representative of the business you represent on the GlossGenius Services.\nrestricted_uses:\n- summary: No personal or consumer use\n  text: Personal, consumer or family use of a Subscription is not intended or permitted.\n- summary: No health-related use without HIPAA steps\n  text: Unless and until you have completed these steps, you shall not use GlossGenius’ services for any health-related\n    purpose\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You further authorize GlossGenius and/or its payment processing partners to perform identity verification\n    and to obtain credit reports or run other background inquiries to assess a Professional’s eligibility to continue\n    using the GlossGenius Services.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are 18 years of age or older and have the legal right and capacity to\n    enter into these Terms\
  \ of Service in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/glossgenius/eligibility/glossgenius-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from GlossGenius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Beauty
- Wellness
- Salon Software
- Payments
- Scheduling
- Business Management
- Software-as-a-Service
---
