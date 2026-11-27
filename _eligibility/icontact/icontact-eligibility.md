---
api_specs:
- filename: icontact-webhooks-asyncapi.yml
  format: yaml
  label: iContact REST API
  slug: rest-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/icontact/asyncapi/icontact-webhooks-asyncapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: neither Customer nor any of its officers, directors or personnel is located in a United States embargoed country
  entity_types:
  - text: if an individual, Customer is at least eighteen (18) years old
    type: individual
  - text: if an entity, it is a company duly organized and validly existing in good standing under the laws of the state in which it was organized
    type: business
  minimum_age:
    text: if an individual, Customer is at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Prohibited content and commerce
    text: iContact expressly prohibits the use of iContact’s website, software or services by any party that engages in, or posts on its website content that relates to, the provision, distribution, display, performance, solicitation, disclosure and/or sale or rent of (as applicable) any of the following (“Prohibited Content”)
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
name: iContact
provenance_date: '2026-11-09'
provider_name: iContact
provider_slug: icontact
slug: icontact-eligibility
source_date: '2026-11-09'
source_filename: icontact-eligibility.yml
source_heading: Eligibility
source_page: https://www.icontact.com/legal/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iContact\naid: icontact\nurl: https://www.icontact.com/legal/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: neither Customer nor any of its officers, directors or personnel is located in a United States embargoed\n    country\nentity_types:\n- type: individual\n  text: if an individual, Customer is at least eighteen (18) years old\n- type: business\n  text: if an entity, it is a company duly organized and validly existing in good standing under the laws of the\n    state in which it was organized\nrestricted_uses:\n- summary: Prohibited content and commerce\n \
  \ text: iContact expressly prohibits the use of iContact’s website, software or services by any party that engages\n    in, or posts on its website content that relates to, the provision, distribution, display, performance, solicitation,\n    disclosure and/or sale or rent of (as applicable) any of the following (“Prohibited Content”)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if an individual, Customer is at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/icontact/eligibility/icontact-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from iContact's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Marketing Automation
- Campaigns
- Contacts
- List
- Segments
- Webhook
- Email Deliverability
- Small Business
---
