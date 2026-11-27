---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least [18] years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least [18] years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: High-stakes decisions about individuals
    text: YOU MUST NOT USE ANY OUTPUT RELATING TO AN INDIVIDUAL PERSON FOR ANY PURPOSE THAT COULD HAVE LEGAL OR SIGNIFICANT CONSEQUENCES FOR THAT PERSON, SUCH AS DECISIONS REGARDING CREDIT, EDUCATION, EMPLOYMENT, HOUSING, INSURANCE, LEGAL MATTERS, MEDICAL ISSUES, OR OTHER CRITICAL AREAS.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access most features of the Service, you must register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sphinx
provenance_date: '2026-11-10'
provider_name: Sphinx
provider_slug: sphinx
slug: sphinx-eligibility
source_date: '2026-11-10'
source_filename: sphinx-eligibility.yml
source_heading: Eligibility
source_page: https://sphinx.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sphinx\naid: sphinx\nurl: https://sphinx.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least [18] years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: High-stakes decisions about individuals\n  text: YOU MUST NOT USE ANY OUTPUT RELATING TO AN INDIVIDUAL PERSON FOR ANY PURPOSE THAT COULD\
  \ HAVE LEGAL OR SIGNIFICANT\n    CONSEQUENCES FOR THAT PERSON, SUCH AS DECISIONS REGARDING CREDIT, EDUCATION, EMPLOYMENT, HOUSING, INSURANCE,\n    LEGAL MATTERS, MEDICAL ISSUES, OR OTHER CRITICAL AREAS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access most features of the Service, you must register for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least [18] years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/sphinx/eligibility/sphinx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sphinx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data Science
- Data Governance
- Analytics
- AI Agents
- Developer Tools
- Jupyter
- LLM
- Data Reliability
---
