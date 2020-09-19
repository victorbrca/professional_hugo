+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Work Experience"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 60

+++

### WMOS Manhattan Support (Consultant)
_**LCBO, Toronto, ON**_
_Aug 2019 - Mar 2020_

#### Responsibilities
- Install SDNs in lower-level and production environments
- Create shell scripts and wrappers for scheduler (Control-M)
- Support technical application issues
- Setup system and app monitoring (SolarWinds)
- Review and identify design gaps and provide solutions

#### Achievements (chronological order)
- Created numerous infrastructure documentation (server layouts, monitoring indexes, load balancer rule list, startup script dependency, endpoint configuration)
- Created multiple startup/shutdown scripts for different scenarios
- Configured monitoring for many different application components with email and Slack (messaging) alerts
- Standardized environment loading scripts and automated the deployment to lower level environments with Ansible
- Created multiple knowledge base articles

* * *

### WMOS Systems Integration Consultant
***Home Hardware Stores Ltd*** -
*May 2012 - Present*

#### Responsibilities
- Responsible for initial design, install and documentation for Manhattan logistics application (WM and Vocollect)
- Designed fail over and load balancing rules for core warehouse application
- Implemented application availability monitoring for all apps via WhatsUpGold, and JBOSS components via JON (JBOSS Operations Network)
- Provided day to day support to the project team and second level support for production
- Build and maintenance of 14x environments

#### Achievements (chronological order)
- Designed a single user profile that loaded application environment variables and aliases based on environment and server type
- Created a start page with links to documents and core apps used by all project teams
- Created a repository for application scripts and a install utility (similar to apt-get) for downloading scripts to application servers
- Created an internal forum used as knowledge base by the project/support middleware team
- Created a centralized server management script (in bash) that allowed administrators to register servers, add ssh-keys to servers, push scripts and run commands on multiple servers
- Created a install script that automated most of the application patch installs (bash and JBOSS)
- Moved all server code for the project to Git (Omnibus GitLab)
- Moved all cron jobs for project servers to a centralized server running Rundeck
- Implemented Puppet with Git (for 12 environments) and auto deployment of server/application code and configuration

* * *

### WMS System Admin
***Shoppers Drug Mart*** -
*June 2010 - May 2012*

#### Tech Lead

- Provided support for all (WMS) Warehouse Management System software (Manhattan's WM, LM, SCI and Vocollect) including RF
scanning devices, voice picking devices and printers
- Administered 4 environments (DEV, SIT, TRN, 2x UAT, 4x PROD), consisting of 15 AIX servers, 12 HP-UX servers and 35 Windows
servers
- Applied weekly patches (Windows, Unix and DB) to applications on all environments
- Created a standard Oracle sqlplus wrapper for sql scripts which became a standard for the project and department
- Developed a logic and method of comparing binaries and script versions between two systems
- Created a solution for a system limitation on the amount of SSH connections coming into a system via script logic

#### Jr Technical Designer

- Working as junior design/engineer for Manhattans business integration application (EIS), was in charge of the design, install and
configuration of the application on new environments, including build books and support documents
- Provided solution for monitoring application, application transactions and database via custom korn and pl/sql scripts, and HP OVO
- Created logic behind fail over via script and load balancer from primary node to HA, and primary site to DR
- Involved in the design and implementation of WM/LM (app and web), SCI and Vocollect on all environments

* * *

### Product Support Specialist
***Accubid Systems*** -
*October 2007 - June 2010*

- Provided product Tech Support on the leader software developer for professional electrical, mechanical and structural cabling estimating
- Support included: installation, software removal, troubleshooting and extensive knowledge of the product
- Dealt with MS-SQL installations
- Decreased the amount of calls by creating various documentations with instructions for the most common problems. These allowed clients to resolve common issues without having to contact support
- Reduced time when migrating clients by creating a package that allowed the conversion of files when skipping one or more versions. Before the package was created it was necessary to install all versions of the program to sequentially convert the files

* * *

### 3Com - Level 2 Tech Support
***Siemens Canada*** -
*April 2005 - October 2007*

#### Wireless Tech Support
- Provided Tech Support on Wireless products and entry level network products (ADSL/DSL routers, APs, switches, wireless switch managers, etc…)
- Developed a forum, chat and product information/start page for L2 technicians resulting into a centralized point of reference for all agents
- Involved in two Six Sigma projects to decrease AHT

#### Acting Team Lead
- Monitored Queue and assigned calls to agents making sure that SLA level stayed within the requirements

#### Floor Walker
- Helped agents with questions in regards to process during region take over
- Responsible for solving RMA problems for the whole US and Canadian region (RDR)
- Created a detailed manual of the process above when task was transferred to another department

#### Level 1 Agent
- Customer Service representative for 3Com call center
- Created RMAs, web registration support and solved order issues
- Point of escalation between Brazilian client’s and service escalation
- Developed a start page for Portuguese agents and a pre-made interactive script page for faster case documentation
