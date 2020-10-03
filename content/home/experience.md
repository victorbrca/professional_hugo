+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Work Experience"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 20

+++

Download my Resume [here](./Resume_2020-09.pdf).

### WMOS Manhattan Support (Consultant)
_**LCBO, Toronto, ON**_
_Aug 2019 - Mar 2020_

#### Responsibilities
- Install weekly patches in lower-level and production environments
- Create shell scripts and wrappers for scheduler (Control-M)
- Support technical application issues
- Setup system and app monitoring (SolarWinds)
- Review and identify design gaps and provide solutions

#### Achievements (chronological order)
- Composed numerous infrastructure documents (server layouts, monitoring indexes, load balancer rule list, startup script dependency, endpoint configuration)
- Scripted multiple application startup/shutdown scripts for different scenarios
- Configured monitoring for different application components with email and Slack (messaging) alerts
- Standardized environment loading scripts and automated the deployment to lower level environments with Ansible
- Authored multiple knowledge base articles

* * *

### WMOS Systems Integration Consultant
***Home Hardware Stores Ltd*** -
*May 2012 - Present*

#### Responsibilities
- Responsible for the initial design, install and documentation of the Manhattan logistics application stack (EEM/MIF 2011/2015, WMOS/MIF 2012/2016 and Vocollect 5.0/5.1) on RHEL 5.6 through 7.2
- Design load balancing, fail-over and high availability rules for the core warehouse application and it’s components
- Setup application availability monitoring for all apps via WhatsUp Gold (Ipswitch), JBOSS Operations Network and numerous Bash scripts
- Provide day to day support during project and warranty phases, followed by second level support for production
- Build and maintenance of 14+ environments

#### Achievements (chronological order)
- Constructed a unified system environment profile (Bash) that loaded application variables and aliases based on the server it was being executed on
- Introduced an internal forum that was utilized as knowledge base by the middleware team
- Designed a start page with links to documents and applications that became a standard launch page for the IT infrastructure/project team
- Authored and maintained a server/environment layout document that was later adopted by the IT infrastructure/project team
- Introduced version control by moving all middleware code to an in-house GitLab server
- Coded numerous support and admin/maintenance scripts and aliases (over 20000 lines of code) used by the middleware team (like printer setup, SSL configuration, system check aliases, etc...)
- Developed a sync script in Bash that downloaded code from a GitLab repo and automatic synced it to servers based on server type
- Configured post Git commit scripts to automatically deploy code to web servers
- Moved all cron jobs for the lower-level environment servers to a centralized scheduling solution (Rundeck)
- Converted the server setup and application install processes to Ansible, cutting down the install time from 4 days to 20 mins
- Converted the sync script to Ansible

* * *

### WMS System Admin
***Shoppers Drug Mart*** -
*June 2010 - May 2012*

#### Tech Lead

- Provided support for all (WMS) Warehouse Management System software (Manhattan’s WM, LM, SCI and Vocollect) including RF scanning devices, voice picking devices and printers
- Administered 4 environments (DEV, SIT, TRN, UAT, PROD), consisting of 15 AIX servers, 12 HP-UX servers and 35 Windows servers
- Applied weekly patches (Windows, Unix and DB) to applications on all environments
- Introduced a Oracle sqlplus wrapper to minimize user errors during vendor patches. The script was sent upstream to the vendor and became standard for software delivery for the project
- Came up with the logic and method of comparing binaries and script versions between two systems
- Designed a solution for a system limitation on the amount of incoming SSH connections via script logic

#### Jr Technical Designer

- Working as junior design/engineer for Manhattans business integration application (EIS), oversaw the design, install and configuration of the application on new environments, including build books and support documentation
- Designed a solution for monitoring application, application transactions and database via custom korn and pl/sql scripts, and HP OVO
- Designed the logic behind a script that handled load balancing, fail over and disaster recovery
- Involved in the design and implementation of the Warehouse and Labor Management systems (WM/LM app and web), the BI application (SCI) and the voice picking and devices stack (Vocollect) on all environments

* * *

### Product Support Specialist
***Accubid Systems*** -
*October 2007 - June 2010*

#### Responsibilities

- Provided product support on the leader software developer for professional electrical, mechanical and structural cabling estimates
- Support included: installation, software removal, troubleshooting and extensive knowledge of the product
- Dealt with MS-SQL installations

#### Achievements

- Decreased the amount of calls by creating various documentations with instructions for the most common problems. These allowed clients to resolve common issues without having to contact support
- Reduced time when migrating clients by creating a package that allowed the conversion of files when skipping one or more versions. Before the package existed it was necessary to install all versions of the program to sequentially convert the files

* * *

### 3Com - Level 2 Tech Support
***Siemens Canada*** -
*April 2005 - October 2007*

#### Wireless Tech Support
- Provided Tech Support on Wireless and entry level network products (ADSL/DSL routers, APs, switches, wireless switch managers, etc...)
- Setup a forum, chat and product information/start page for L2 technicians resulting into a centralized point of reference for all agents
- Involved in two Six Sigma projects to decrease AHT

#### Acting Team Lead
- Monitored Queue and assigned calls to agents making sure that SLA level stayed within the requirements

#### Floor Walker
- Helped agents with questions in regards to process during region take over
- Responsible for solving RMA problems for the whole US and Canadian region (RDR)
- Created a detailed manual of the process above when task was transferred to another department

#### Level 1 Agent
- Customer Service representative for 3Com call center
- Dealt with RMAs, web registration support and solved order issues
- Point of escalation between Brazilian client’s and service escalation
- Designed a start page for Portuguese agents and a pre-made interactive script page for faster case documentation
