---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you purchase a Plan for individuals ("Individual Plan") through our site
    type: individual
  - text: If you purchase a Plan for businesses ("Business Plan") through our Site or through a separate DataCamp provided order form
    type: business
  - text: The Classrooms Plan can only be used in an educational setting by professors, teachers or instructors.
    type: other
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR SERVICE IF YOU ARE NOT AT LEAST 16 YEARS OLD (UNLESS YOU ARE A CLASSROOMS USER).
    value: '16'
  restricted_uses:
  - summary: No reliance on AI for high-stakes decisions
    text: You may not (a) rely on AI Tutor Content or AI Outputs as the basis for legally binding, high-stakes, or safety-critical decisions affecting individuals
  - summary: No automated employment or admissions decisions using AI Tutor Content
    text: use AI Tutor Content to make or support automated decisions relating to employment, promotion, termination, compensation, admissions, eligibility, or similar determinations
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right, in our absolute discretion, to determine your eligibility for a Classrooms Plan
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DataCamp
provenance_date: '2026-11-09'
provider_name: DataCamp
provider_slug: datacamp
slug: datacamp-eligibility
source_date: '2026-11-09'
source_filename: datacamp-eligibility.yml
source_heading: Eligibility
source_page: https://www.datacamp.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataCamp\naid: datacamp\nurl: https://www.datacamp.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you purchase a Plan for individuals (\"Individual Plan\") through our site\n- type: business\n  text: If you purchase a Plan for businesses (\"Business Plan\") through our Site or through a separate DataCamp\n    provided order form\n- type: other\n  text: The Classrooms Plan can only be used in an educational setting by professors, teachers or instructors.\nrestricted_uses:\n- summary: No reliance\
  \ on AI for high-stakes decisions\n  text: You may not (a) rely on AI Tutor Content or AI Outputs as the basis for legally binding, high-stakes, or\n    safety-critical decisions affecting individuals\n- summary: No automated employment or admissions decisions using AI Tutor Content\n  text: use AI Tutor Content to make or support automated decisions relating to employment, promotion, termination,\n    compensation, admissions, eligibility, or similar determinations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right, in our absolute discretion, to determine your eligibility for a Classrooms Plan\nminimum_age:\n  value: '16'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR SERVICE IF YOU ARE NOT AT LEAST 16 YEARS OLD (UNLESS YOU ARE A CLASSROOMS\n    USER).\n"
source_yaml_url: https://artifacts.apis.io/datacamp/eligibility/datacamp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from DataCamp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Science
- Education
- E-Learning
- Online Courses
- Data Analytics
- Python
- R
- SQL
- EdTech
- Upskilling
- Artificial Intelligence
---
