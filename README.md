# zeta-types-web

A web client for working with zeta-types and tannakian symbols.

## Architecture plan

Host/Framework: Firebase
Computation: SageMathCloud/CoCalc

CoCalc should open a socket between it and the Firebase server, where code from firebase is sent to cocalc for processing.

## Planned features of the web-app

* Authentication system
* Three sections; home (info), browse (browse data), contribute (add data), and maybe a blog or something similar.

### Home

Information about the project, as well as the articles.

### Browse

Browse and search for zeta-types and tannakian symbols. View entries. Should have an API, so that data can be used by automated programs. Think of ways to search trough database efficiently.

### Contribute

Adding data. Either directly, or by writing sage-code which generates the data. Begin with just zeta-types and tannakian symbols, expand to code later. Some form of authentication necessary to contribute. Should inform of potential duplicate entries.

