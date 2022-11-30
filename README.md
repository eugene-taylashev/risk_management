Risk Assessment
===============

This repository contains a set of IT Risk Management tools
* [Risk Assessment Simplified.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/Risk%20Assessment%20Simplified.xlsx) - MS Excel spreadsheet with template to perform Simple Risk Assessment (see Methodology below)
  * [Risk-Project-Big List Simplified.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/Risk-Project-Big%20List%20Simplified.xlsx) - Extended list of risks for an IT project for Simple Risk Assessment
* [FMEA assessment.xls](https://github.com/eugene-taylashev/risk_management/blob/master/FMEA%20assessment%202.xls) - MS Excel spreadsheet with template to perform FMEA IT risk assessment
* [Risk Assessment Advanced.xlsx](https://github.com/eugene-taylashev/risk_management/blob/master/Risk%20Assessment%20Advanced.xlsx) - MS Excel spreadsheet with template to perform ISO 27005-based Risk Assessment

All files are under the terms of the [MIT License](https://github.com/eugene-taylashev/risk_management/blob/master/license.txt).

## Simple Risk Assessment Methodology

This is a simple Risk Assessment method also called Brewer-List Approach. This method could be used to perform a quick risk assessment for a project or an initiative.

**Step 1**: Produce list of concerns. This list does not have to be full.

**Step 2**: Analyze concerns and split them into events and impacts or consequences.

**Step 3**: Estimate frequency or probability (FoP) for events.  Use the following suggested logarithmic scale: 1-Rare (once a decade), 2-Unlikely (once a year), 3-Possible (once a month), 4-Likely (every few days), 5-Almost certain (several times a day). 

**Step 4**: Estimate severity of the business impact (Sev) should the event occur. Use the following suggested logarithmic scale: 1 -Insignificant ($100), 2 -Minor ($1K), 3 -Moderate ($10K), 4 -Major ($100K), 5 -Catastrophic  ($1M). Or use men-hour instead of dollar values.

**Step 5**: Pair events with impacts to calculate inherent risk. 

**Step 6**: Identify risks which require treatment and consider treatment options. Treatment options could be: 2-Accept Risk (i.e. Do nothing), 3-Modify (reduce) Risk, 4-Transfer Risk (i.e. insurance or third-party service), 5-Avoid Risk.  Usually preventive and detective compensating controls modify FoP, corrective (reactive) controls modify Sev.

**Step 7**: Based on treatment plan, estimate the residual risk and made final decision about these risks.  
