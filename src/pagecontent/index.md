> This implementation guide is not fully complete.
{: .stu-note }

## Overview
This implementation guide is based on FHIR Version 4.0.0 and defines the minimum conformance requirements necessary for exchanging clinical trial data. Typically, this exchange will be between a clinical trial site and a clinical trial sponsor.
  

The FHIR profiles referenced in this guide are closely aligned with the profiles as defined in [US Core](http://www.hl7.org/fhir/us/core/).

The main distinguishing factor of the profiles contained in this guide is the emphasis on de-identification of patient data, and the usage/adoption of the "Research" FHIR Resources 
``ResourceSubject`` and ``ResearchStudy``. 


## Use Cases
This implementation guide describes several use cases and sets search expectations for each.

- A research study sponsor requests laboratory data for a research study
- A research study sponsor request vital signs data for a research study

Additional use cases TBA.

