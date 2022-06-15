# Main

This repository is the main repository for our artifact release for `Keeping Privacy Labels Honest` a publication in the Proceedings on Privacy Enhancing Technologies Symposium 2022`.
In this repository you will find our bibtex, our acknowledgements, and further guidance on the structure of this github org containing the relevant artifacts. 
If you have any questions, feel free to open a ticket or simply email us.

Please be aware that most of the work was done in 2021 and leveraged API endpoints might have gone dead by now or slightly changed in how to access them. 

## Contents

This artifact release contains our raw data set of all Privacy Labels we evaluated as well as the source code for actually downloading privacy labels, analyzing privacy labels, automating traffic collection on an iPhone, as well as analyzing the collected traffic.

### Privacy Labels

[This](https://github.com/Keeping-Privacy-Labels-Honest/privacyLabels) is our raw data set containing all analyzed privacy labels.

### Privacy Label Downloader

[This](https://github.com/Keeping-Privacy-Labels-Honest/IndiaPaleAle) is the tool to use the 3u API to get a list of app ids that can then be used to download privacy labels from the Apple store.

### iPhone automation

[This](https://github.com/Keeping-Privacy-Labels-Honest/ios-app-analyzer) is our script for automating the install, run, and stop of different apps on the iPhone. You require an jailbroken iPhone as well as a set of IPA files linked to the account on that iPhone.

### Analyzing Privacy Labels and Traffic 

[This](https://github.com/Keeping-Privacy-Labels-Honest/ledeco) is our main tool. It will analyze a given set of privacy label and generate pretty graphs, as well as also analyze the traffic collected when running apps on the iPhone.


# Acknowledgements

- This project was conceived and executed at the [Institute for Application Security (Technische Universität Braunschweig)](https://www.tu-braunschweig.de/ias)

- This project has received funding from the European Union’s Horizon 2020 research and innovation  programme under grant agreement No 101019206.

- This project has received funding by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) under Germany’s Excellence Strategy - EXC 2092 CASA - 390781972. 

- [Datenanfragen.de e. V.](https://www.datarequests.org) is a non profit organisation co-founded by one of our authors (Benjamin Altpeter), they will further use the technology developed during this project to fight for our privacy rights.


# BibTex
``` 
@inproceedings{PETS:Koch:2022,
 author = {Simon Koch and Malte Wessels and Benjamin Altpeter and Madita Olvermann and Martin Johns},
 title  = {Keeping Privacy Labels Honest},
 booktitle = {Proceedings on Privacy Enhancing Technologies Symposium (PoPETS 2022)},
 year = {2022}
}
```
