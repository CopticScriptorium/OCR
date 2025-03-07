# OCR
Repository for development files and documentation for Coptic OCR in development by Coptic Scriptorium. 

Some of this work is based on prior work from other researchers that was shared publicly. Please credit the prior researchers along with Coptic Scriptorium.

## OCR4All files
Models and training files for [OCR4All](https://www.ocr4all.org/) were developed from [original work by Eliese-Sophia Lincke, et al.](https://vcs.etrap.eu/Coptic-OCR/datasets). The OCR4All team converted the training files and produced a model for the newer version of OCR4All and provided them to Coptic Scriptorium. We then built refined, specialized models.

Citations:
Eliese-Sophia Lincke, Kirill Bulert & Marco Büchler, "Optical Character Recognition for Coptic fonts: A multi-source approach for scholarly editions," in: DATeCH2019 Proceedings of the 3rd International Conference on Digital Access to Textual Cultural Heritage, 87-91. open access; DOI: 10.1145/3322905.3322931

Christian Reul, Dennis Christ, Alexander Hartelt, Nico Balbach, Maximilian Wehner, Uwe Springmann, Christoph Wick, Christine Grundig, Andreas Büttner, and Frank Puppe, "OCR4all—An Open-Source Tool Providing a (Semi-)Automatic OCR Workflow for Historical Printings" Appl. Sci. 2019, 9(22), 4853; https://doi.org/10.3390/app9224853

## File Structures
Data in the "Processed OCR" directory have been OCR'd and ground truth has been produced. 
 - Meta files within subdirectories contain metadata information.
 - These documents can be routed through the publication process when ready (see publication issue threads for more information)

The other directories named after editions and editors contain OCR input, output, and unprocessed results (but as ground truth -- no post-processing after ground truth). These documents have been or will be uploaded to GitDox. Check the GH repository information in GitDox for the location of each document. 
 - As of August 2024, the Sahidic documents from Budge editions are all in the Budge-dev repository.
 - The gitdox subdirectory here should be used for documents manually edited in GitDox that are not from a Budge edition

Models are in the "models" subdirectory.
