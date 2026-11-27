---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Site on behalf of a company or other legal entity, you represent that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years of age (or the age of majority in their jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Prohibited AI uses
    text: Do not use AI Features to generate content that is deceptive or misleading (including undisclosed synthetic media intended to deceive)
  - summary: Sensitive data in AI inputs
    text: Do not submit AI Inputs that contain sensitive personal information (such as government identifiers, health information, or payment card data)
  - source: https://www.rainfocus.com/privacy-security/api-terms-and-conditions/
    summary: Unlawful or harmful use
    text: use the Developer Tools for unlawful, harmful, deceptive, or unauthorized purposes, or knowingly enable end users to violate applicable law, regulation, or these terms.
  - source: https://www.rainfocus.com/privacy-security/api-terms-and-conditions/
    summary: Personal data through AI tools
    text: Customer will not process personal data through any AI tool or third-party integration unless Customer has all required rights, consents, and contractual protections.
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
name: RainFocus
provenance_date: '2026-11-10'
provider_name: RainFocus
provider_slug: rainfocus
slug: rainfocus-eligibility
source_date: '2026-11-10'
source_filename: rainfocus-eligibility.yml
source_heading: Eligibility
source_page: https://www.rainfocus.com/privacy-security/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RainFocus\naid: rainfocus\nurl: https://www.rainfocus.com/privacy-security/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.rainfocus.com/privacy-security/api-terms-and-conditions/\n  - https://www.rainfocus.com/privacy-security/terms-of-use/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Site on behalf of a company or other legal entity, you represent that you have the\n    authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Prohibited AI uses\n  text: Do not use AI Features to generate content\
  \ that is deceptive or misleading (including undisclosed synthetic\n    media intended to deceive)\n- summary: Sensitive data in AI inputs\n  text: Do not submit AI Inputs that contain sensitive personal information (such as government identifiers, health\n    information, or payment card data)\n- summary: Unlawful or harmful use\n  text: use the Developer Tools for unlawful, harmful, deceptive, or unauthorized purposes, or knowingly enable\n    end users to violate applicable law, regulation, or these terms.\n  source: https://www.rainfocus.com/privacy-security/api-terms-and-conditions/\n- summary: Personal data through AI tools\n  text: Customer will not process personal data through any AI tool or third-party integration unless Customer has\n    all required rights, consents, and contractual protections.\n  source: https://www.rainfocus.com/privacy-security/api-terms-and-conditions/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: The Site is intended for users who are at least 18 years of age (or the age of majority in their jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/rainfocus/eligibility/rainfocus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from RainFocus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Event
- Event Management
- Event Marketing
- Registration
- Conferences
- Webinars
- Marketing Technology
- Attendee Data
- MCP
- Agents
- Enterprise Software
- Software-as-a-Service
---
