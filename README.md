# awesome-cern
An opinionated curated list of awesome open source frameworks, libraries and software developed by CERN for the world.

*(OS Compatibility Key: L=Linux, M=macOS, W=Windows, WSL=Windows Subsystem for Linux, Browser=Web Browser Interface, Server=Server Component, Client=Client Component, Dev=Development Environment)*

## Engineering
- [EAM Light](https://eam-opensource.web.cern.ch/content/eam-light) *(OS: Browser)*: light-weight web application for HxGN EAM.

## Open Science

### Digital repositories
- [InvenioILS](https://inveniosoftware.org/products/ils/) *(OS: Server: L; Dev: L, M, W (Docker recommended))*: a modern and user-friendly integrated library system, written in Python and React.
- [InvenioRDM](https://inveniosoftware.org/products/rdm/) *(OS: Server: L; Dev: L, M, W (Docker recommended))*: turn-key research data management (RDM) digital repository platform based on [Invenio Framework](https://inveniosoftware.org/products/framework/) and [Zenodo](https://www.zenodo.org/), written in Python and React.
- [Open Data Portal](https://github.com/cernopendata) *(OS: Browser (Server: L))*: highly curated repository of high energy physics (UI and server), written in Python.
- [REANA](https://reana.io/) *(OS: Server: L (Kubernetes); Client: L, M, W(WSL))*: a reproducible research data analysis platform.
- [Zenodo](https://github.com/zenodo/zenodo-rdm) *(OS: Server: L; Dev: L, M, W (Docker recommended))*: Research. Shared. An open dependable home for the long-tail of science.

### Event Management
- [Indico](https://getindico.io) *(OS: Browser (Server: L))*: feature-rich general event management system written in Python.
- [newdle](https://github.com/indico/newdle) *(OS: Browser (Server: L))*: a lightweight collaborative enterprise meeting scheduling tool

## Physics/mathematics analysis/simulation
- [ACTS](https://github.com/acts-project/acts) *(OS: L, M, W)*: Experiment-independent toolkit for (charged) particle track reconstruction in high energy an nuclear physics experiments
- [BioDynaMo](https://www.biodynamo.org/home-page) *(OS: L, M, W (Native/WSL))*: create, run, and visualise multidimensional agent-based simulations in various domains.
- [CAiMIRA](https://github.com/CERN/CAiMIRA/) *(OS: L, M, W (Docker/WSL recommended for W))*: CERN Airborne Model for Indoor Risk Assessment, a tool developed to assess and model the concentration of airborne viruses in enclosed spaces, specifically focusing on the SARS-CoV-2 virus. Documentation available [here](https://caimira.docs.cern.ch/).
- [Geant4](https://geant4.web.cern.ch/) *(OS: L, M, W)*: Toolkit for the simulation of the passage of particles through matter.
- [ROOT](https://root.cern/) *(OS: L, M, W)*: an open-source data analysis framework used by high energy physics and others.
- [Xsuite](https://xsuite.web.cern.ch) *(OS: L, M, W)*: A collection of Python packages for simulating beam dynamics in particle accelerators with support of different computing platforms, such as OpenMP and various GPU frameworks.

## Security
- [pam_2fa](https://github.com/CERN-CERT/pam_2fa) *(OS: L (Possibly M))*: PAM 2FA module provides a second factor authentication, to be combined with the standard PAM-based password.

## Storage and Data

### Data management
- [FTS](https://fts.web.cern.ch/fts/) *(OS: Server: L; Client: L, M, W)*: software written in C++/Python to orchestrate reliable and large-scale data transfers.
- [Rucio](https://rucio.cern.ch) *(OS: Server: L; Client: L, M, W)*: software written in Python to manage large volumes of data spread across data centres.
- [Davix](https://davix.web.cern.ch/) *(OS: L, M, W)*: toolkit for file operations over HTTP and Cloud protocols (written in C++).

### Storage systems
- [EOS](https://eos-web.web.cern.ch/eos-web/) *(OS: Server: L; Client: L, M, W (varying methods))*: distributed storage system written in C++ for the exabyte era (biggest installation 1.1 Exabytes).
- [CTA](https://eoscta.docs.cern.ch/latest/) *(OS: Server: L)*: distributed storage system written in C++ for archival of data on tape media (biggest installation 1 exabyte).
- [CVMFS](https://cernvm.cern.ch/filesystem/) *(OS: Server: L; Client: L, M, W(WSL))*: a scalable, reliable and low-maintenance software distribution service.
- [QuarkDB](https://quarkdb.web.cern.ch/quarkdb/docs/master/) *(OS: L)*: high-performance C++ key-value datastore built with: RocksDB + Raft + Redis wire protocol (RESP2).
- [Reva](https://github.com/cs3org/reva) *(OS: Server: L)*: WebDAV/gRPC server to connect end-users to storage system (EOS, CephFS). Written in Go.

## Libraries

### Flask
- [flask-multipass](https://github.com/indico/flask-multipass) *(OS: L, M, W)*: multi-backend authentication system for Flask
- [flask-pluginEngine](https://github.com/indico/flask-pluginengine/) *(OS: L, M, W)*: a simple plugin system for Flask applications
- [js-flask-urls](https://github.com/indico/js-flask-urls) *(OS: Browser / Node.js (L, M, W))*: get Flask blueprint URLs in your JS apps, the clean way

### UI
- [react-jsx-i18N](https://github.com/indico/react-jsx-i18n) *(OS: Browser (Dev: L, M, W))*: Gettext-enhanced React components
- [react-overridable](https://github.com/indico/react-overridable) *(OS: Browser (Dev: L, M, W))*: Overridable React components.
- [React-SearchKit](https://github.com/inveniosoftware/react-searchkit) *(OS: Browser (Dev: L, M, W))*: React components library to build search interfaces.