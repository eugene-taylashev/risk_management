Risk Assessment
===============

This repository contains a set of IT Risk Management tools
* [Risk Assessment Simplified.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/Risk%20Assessment%20Simplified.xlsx) - MS Excel spreadsheet with template to perform Simple Risk Assessment (see Methodology below)
  * [Risk-Project-Big List Simplified.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/Risk-Project-Big%20List%20Simplified.xlsx) - Extended list of risks for an IT project for Simple Risk Assessment
* [FMEA assessment.xls](https://github.com/eugene-taylashev/risk_management/blob/master/FMEA%20assessment%202.xls) - MS Excel spreadsheet with template to perform FMEA IT risk assessment
* [Risk Assessment Advanced.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/Risk%20Assessment%20Advanced.xlsx) - MS Excel spreadsheet with template to perform ISO 27005-based Risk Assessment
* [ISO 27001 Statement of Applicability.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/ISO%2027001%20Statement%20of%20Applicability.xlsx) - MS Excel spreadsheet to assist in achieving and maintaining ISO/IEC 27001:2022 certification (see ISO 27001 SoA below)

All files are under the terms of the [MIT License](https://github.com/eugene-taylashev/risk_management/blob/master/license.txt).

## ISO 27001 SoA
This Excel spreadsheet is a comprehensive support tool designed to assist in achieving and maintaining ISO/IEC 27001:2022 certification. It provides an integrated view by linking relevant risks, policies, control owners, and Annex A controls to support the justification for inclusion or exclusion of each control.

The tool can be used for multiple purposes, including:
* **Statement of Applicability (SoA)**: Mapping and rationale for Annex A control applicability.
* **Risk Register**: Includes a sample risk rating methodology and example entries.
* **Audit Workpapers**: Sample content provided to guide internal or external audit preparation.
* **Policy Content Verification**: Cross-checking policies against control requirements.
* **Glossary of Terms and Definitions**: Includes common terminology used in ISMS documentation.
* **List of IT Acronyms**: Reference list of typical information security and IT-related acronyms.

This spreadsheet can serve as a central reference for ISMS stakeholders, simplifying compliance tracking and documentation efforts.


## Simple Risk Assessment Methodology

This is a simple Risk Assessment method also called Brewer-List Approach. This method could be used to perform a quick risk assessment for a project or an initiative.

**Step 1**: Produce list of concerns. This list does not have to be full.

**Step 2**: Analyze concerns and split them into events and impacts or consequences.

**Step 3**: Estimate frequency or probability (FoP) for events.  Use the following suggested logarithmic scale: 1-Rare (once a decade), 2-Unlikely (once a year), 3-Possible (once a month), 4-Likely (every few days), 5-Almost certain (several times a day). 

**Step 4**: Estimate severity of the business impact (Sev) should the event occur. Use the following suggested logarithmic scale: 1 -Insignificant ($100), 2 -Minor ($1K), 3 -Moderate ($10K), 4 -Major ($100K), 5 -Catastrophic  ($1M). Or use men-hour instead of dollar values.

**Step 5**: Pair events with impacts to calculate inherent risk. 

**Step 6**: Identify risks which require treatment and consider treatment options. Treatment options could be: 2-Accept Risk (i.e. Do nothing), 3-Modify (reduce) Risk, 4-Transfer Risk (i.e. insurance or third-party service), 5-Avoid Risk.  Usually preventive and detective compensating controls modify FoP, corrective (reactive) controls modify Sev.

**Step 7**: Based on treatment plan, estimate the residual risk and made final decision about these risks.  
