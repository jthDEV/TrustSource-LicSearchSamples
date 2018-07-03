# TrustSource-LicSearchSamples

This repository contains different use cases to simulate the distribution of license information. When researching for license conditions, the researcher often has a magnitude of issues: Licenses that claim to be type A but actually are type B or they may contain additional clauses. Also it may happen that a main component is of license A but a linked or subcomponent is of type C or E, not in compliance with license A, etc.

To support a safe and secure resolution of these issues, this data is aimed to provide test data, simulating all kind of strange situations found in real world scenarios.

You are invited to add strange cases. Please create your own folder for your cases and leave a short discription describing the case as well as the good and bad conditions.
Thank you

All contributions will be made under CC-0.

## Directories
 * 01 - PlainLictxt-ext - contains license textes with additional license holder information
 * 02 - LicUndercover - conatins licenses that run under fake flags, eg. GPL-1.1 claiming GPL or GPL-2.0
 * 03 - LicModAddons - contains samples with additional clauses
 * 04 - LicModReduced - contains samples with some clauses removed
 * 05 - LicModCombined - contains samples with both clauses removed and clauses added
 * 10 - LicComb - contains components with different licenses
 * 11 - LicCombUnfit - contains components with licenses that do not fit together 


TODOS:
- provide committer agreement
