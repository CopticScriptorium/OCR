# Coptic Scriptorium OCR Models
This directory contains the models for OCR4All developed and/or used by the Coptic Scriptorium Project. All models were built and trained by Dr. Lydia Bremer-McCollum, postdoctoral researcher 2023-2024, except for "coptic-all." "Coptic-all" is the base model from which all the other models were developed. "Coptic-all" was derived from the model developed by Lincke et al. (see below) for an earlier version of the [OCR4All software](https://www.ocr4all.org/). The OCR4All team kindly converted it for use in the OCR4All version available in 2023. 

The titles of the subdirectories of the models should be self-explanatory for Coptic Studies researchers. We provide the following additional information for ease of use:
* AmelineauIsaacBohairicModel was trained on Amélineau's editions of the Life of Isaac and the Lausiac history
* "all" models were trained on multiple editions that used the same font/characterset (typically edited by the same editor); usually we have more than one fine-tuned model trained on specific individual works by the same editor, and "all" indicates the model has been trained on "all" the editions by that editor/with that typeface we have processed to distinguish. So, _e.g._ BudgeAll is the model trained on multiple works edited by Budge, as opposed to BudgeApaPsoteMisc, which has been fine-tuned on Budge's edition of the Teachings of Apa Psote.
* the Crum model was also partially trained on an edition published by Sobhy

## Citations 
Eliese-Sophia Lincke, Kirill Bulert & Marco Büchler, "Optical Character Recognition for Coptic fonts: A multi-source approach for scholarly editions," in: DATeCH2019 Proceedings of the 3rd International Conference on Digital Access to Textual Cultural Heritage, 87-91. open access; DOI: 10.1145/3322905.3322931

Christian Reul, Dennis Christ, Alexander Hartelt, Nico Balbach, Maximilian Wehner, Uwe Springmann, Christoph Wick, Christine Grundig, Andreas Büttner, and Frank Puppe, "OCR4all—An Open-Source Tool Providing a (Semi-)Automatic OCR Workflow for Historical Printings" Appl. Sci. 2019, 9(22), 4853; https://doi.org/10.3390/app9224853

## Funding and Support
The development of these OCR models was primarily funded by an Implementation grant from the National Endowment for the Humanities division of Humanities Collections and Reference Resources. (The grant was prematurely terminated in 2025 by DOGE and is being reinstated in 2026. The HCRR division itself no longer exists.)
The Office of the Vice Provost for Research and Partnerships at the University of Oklahoma provided additional financial support.
The Data Institute for Societal Challenges provided server space and management; we especially thank Dr. Wolfgang Jentner.
