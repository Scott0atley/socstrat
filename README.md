# socstrat
Stata program to compute and analyze social stratification variables

socstrat is designed to calculate and analyze social stratification variables based on two variables: the National Statistics Socio-Economic Classification (NS-SEC) or Registrar General's Social Class (RGSC). The command requires at least two variables to define the standard occupation classification (SOC) code and the employment status (via the socstatus() option and generates a new variable that represents the computed social stratification variable.

socstrat uses a range of sources to derive the eight-level NS-SEC full analytic class and seven-level full analytic RGSC class schemas based on SOC 1990, 2000, 2010, and 2020. Importantly, RGSC has not been updated for SOC 2020 level and as such, if a user attempts to generate RGSC based on that particular SOC, an appropriate error message will be provided. NS-SEC and RGSC SOC 90 derivation tables are produced by Lambert (2003). SOC 2000 and S0C 2010 derivation tables for RGSC are provided by Rose and Pevalin (2011) as part of a ERSC Review of Government Social Classifications and as part of a reserach grant from the British Academy. NS-SEC derivations for SOC 2000, 2010, and 2020 are provided by official SOC derivation guides produced by the Institue for Social and Economic Reserach (ISER) and the Office of National Statistics (ONS). 

References
	Lambert, P.S. and Prandy, K. (2003) CAMSIS project webpages: Cambridge Social Interaction and Stratification Scales, Retreived 06/01/2025 from http://www.camsis.stir.ac.uk/ .
	
	Lambert, P.S. (2003) CAMSIS for Britain, SOC90 (electronic file, version 0.1, date of release: February 2003), Retrieved 06/01/2025 from http://www.camsis.stir.ac.uk/downloads/gb91soc2000.zip .
	
	Rose, D. and Pevalin, D. (2001) The National Statistics Socio-economic Classification: Unifying Official and Sociological Approaches to the Conceptualisation and Measurement of Social Class. ISER Working Papers. Paper 2001-4. Colchester: University of Essex. Available at: https://www.iser.essex.ac.uk/research/publications/working-papers/iser/2001-04
	
	Rose, D. and Pevalin, D. (2011) Derivations of Social Class, Retrieved 06/01/2025 from https://www.iser.essex.ac.uk/archives/nssec/derivations-of-social-class .
	
	SOC2010 Volume 3: the National Statistics Socio-economic classification (NS-SEC rebased on SOC2010). Retrieved 06/01/2025 Online at: https://www.ons.gov.uk/methodology/classificationsandstandards/standardoccupationalclassificationsoc/soc2010/soc2010volume3thenationalstatisticssocioeconomicclassificationnssecrebasedonsoc2010
	
	SOC 2020 Volume 3: the National Statistics Socio-economic Classification (NS-SEC rebased on the SOC 2020). Retrieved 06/01/2025 Online at: https://www.ons.gov.uk/methodology/classificationsandstandards/standardoccupationalclassificationsoc/soc2020/soc2020volume3thenationalstatisticssocioeconomicclassificationnssecrebasedonthesoc2020 


Author:
Scott Oatley
Department of Sociology
University of Edinburgh
Edinburgh
Email: soatley@ed.ac.uk

