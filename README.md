# zeta-types-web

A web client for working with zeta-types and tannakian symbols.

## Architecture plan

Client-side: Bootstrap w/ React (or vue.js or angular, haven't decided)
Host/Framework: Firebase
Computation: CoCalc

CoCalc should open a socket between it and the Firebase server, where code from firebase is sent to cocalc for processing.

## Planned features of the web-app

* Authentication system
* Three sections; home (info), browse (browse data), contribute (add data), and maybe a blog or something similar.
* API keys if need be (distributed first on a person by person basis)
* It would be nice to have a console for computation without API keys
* There should be some theory available, similar to LMFDB. Should include support for latex, maybe something like markdown


### Home

Information about the project, as well as the articles.

### Browse

Browse and search for zeta-types and tannakian symbols. View entries. Should have an API, so that data can be used by automated programs. Think of ways to search through database efficiently.

### Contribute

Adding data. Either directly, or by writing sage-code which generates the data. Begin with just zeta-types and tannakian symbols, expand to code later. Some form of authentication necessary to contribute. Should inform of potential duplicate entries.

## Style

### Color scheme
Not decided, something blueish maybe. Perhaps mostly grays and whites.

### Logo
Perhaps the Tannakian symbol {1}/{p} or something similar. Maybe a stylized zeta.

### Fonts
Roboto, Open Sans, and maybe Oxygen.


