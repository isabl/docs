# Home

Isabl is a plug-and-play open-source framework for scalable bioinformatics operations designed to support automated processing and management of NGS assets and their metadata. Isabl's patient centric model enables advanced integrations with multinomial data types and linkage to other institutional information systems such as clinical databases and visualization interfaces.

{% page-ref page="quick-start.md" %}

### Features

* 👾 **Backend, Data Model and RESTful API**
  * Fully featured and brisk RESTful API with extensive swagger documentation
  * Comprehensive permissions controls and user groups
  * Patient centric relational model with support for:

    * _Individuals_, _samples_, sequencing _experiments_ and _cohorts_
    * _Assembly_ aware bioinformatics _applications_ and _analyses_
    * Choice models such as _diseases_, _centers_ and more
    * **Custom fields** for all schemas
* 🤖 **Command Line Interface and Software Development Kit**

  * NGS Assets Management \(Permissions, Storage, Tracking\)
  * Automated execution and tracking of bioinformatics applications
  * Project and patient level results auto-merge
  * Operational automations on data import and analyses status change
  * Dynamic retrieval of data and results using versatile queries
  * Fully featured SDK for post-processing analyses

* 🚀 **Web Application**

  * User Interface to browse and manage the operations metadata
  * Analyses tracking and results visualization
  * Flexibility to edit and customize models
  * Batch creation of metadata by excel file submission
  * Single Page Application that provides a crispy user experience
  * Possibility to integrate third-party services like JIRA

* ✅ **Plug-n-play and reliable codebase**
  * Docker-compose is the only dependency for the web application and the backend
  * The Command Line Interface is a portable pip installable package
  * Continuously Integrated with +98 % coverage across all codebase
  * isabl is upgradable, no need to fork out from codebase

### Infrastructure

It is composed of an extensible relational database \(Isabl-db\), a comprehensive RESTful API \(Isabl-API\), a Command Line Client \(Isabl-CLI\), and a front end single page web application \(Isabl-web\).

![Isabl Infrastructure](https://docs.google.com/drawings/d/e/2PACX-1vQnO2UBtPAGuUqobgfAH2GFbvuE5aCAzrYpxa_nBb8tigeT-GdfAkurTnOpzrpa_QDxBH-nrQ-lnxEk/pub?w=998&h=712)

### Data Model

![](https://docs.google.com/drawings/d/e/2PACX-1vTG3QBMOtwM5DhpFG07iQFj0SA0J7CE4e8Xd3ZJcpJy24EiDu9HbGomqslNFgqV3rauJ-z_VU-SY-ja/pub?w=1305&h=791)

### Why Isabl

Isabl ensures that all bioinformatics operations follow the DATA reproducibility checklist \(Documentation, Automation, Traceability, and Autonomy\), whilst guarantees that assets are managed according to the FAIR principles \(Findable, Interoperable, Accessible, Reusable\).

![](https://docs.google.com/drawings/d/e/2PACX-1vRCagXfy-ubxEHKL3GOSTTEGE1g9hWk1Ic0yTx3tWsBJHWSIfO5Y2Hcu0wTeBtb3mA1DeEXKw4c1fBd/pub?w=1216&h=810)

Here are some reasons why you may want to use Isabl:

* You don't have a +10 engineers group but do have hundreds of samples
* You'll rather not have your data managed by postdocs, PhD students
* Crosslink samples from different cohorts
* Answer new questions using existing data
* Full log and audit trail of your informatics operations
* Automatically merge results as new samples are added to big cohorts
* You want to have programmatic access to the entire data capital
* Seamlessly run reproducible pipelines across your projects

{% embed url="https://www.youtube.com/watch?v=L1JhVqZ3oBY" %}

### Similar projects

* [The Genome Modeling System](https://github.com/genome/gms) _Genome Institute at Washington University platform._
* [SeqWare](https://seqware.github.io/) _analyze massive genomics datasets._
* [QuickNGS](http://bifacility.uni-koeln.de/quickngs/web/) _efficient high-throughput data analysis of Next-Generation Sequencing data._
* [HTS-flow](https://github.com/arnaudceol/htsflow) _a framework for the management and analysis of NGS data._

### What Isabl is not

* Isabl is not a _Workflow Management System_ such as [toil](https://github.com/DataBiosphere/toil), [bpipe](https://github.com/ssadedin/bpipe), instead Isabl facilitates automated deployment and databasing of data processing pipelines.

* Isabl is not a P_latform as a Service \(PAAS\)_ provider such as [DNA nexus](https://www.dnanexus.com), [Seven Bridges](https://www.sevenbridges.com) or [Fire Cloud](https://software.broadinstitute.org/firecloud/), instead an information system that could potentially feed in metadata and data to these services. 
* Isabl differs from _Server Workbenches_ such as [Galaxy](https://usegalaxy.org/) or Pegasus, instead of being configuration friendly, Isabl is designed to conduct systematic analyses automatically and in a standardized way with as little human input as possible. 
* Isabl is not a _Workflow Language_, instead the Bioinformatics Applications in `isabl` only define meta-data driven validation and logic to build commands to trigger pipelines written in any language.

