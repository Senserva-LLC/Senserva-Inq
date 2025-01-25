<img align="center" height="50" src="https://github.com/user-attachments/assets/5ce51b46-cdd7-4828-926c-9e9c3ec82460">

*Know your Entra ID Security State in minutes!*

# $${\color{LimeGreen}The} {\color{LimeGreen}Senserva} {\color{LimeGreen}Inquisitor}$$
This is **Beta 1** of the $${\color{LimeGreen}Inquisitor}$$ and can be used by either IT teams or Security teams to do quick or depth security reviews.  This release is for Windows, Linux Container version coming in a not too distant release.

> [!IMPORTANT]
>  Mark Shavlik here, $${\color{LimeGreen}The} {\color{LimeGreen}Senserva} {\color{LimeGreen}Inquisitor}$$ is designed to be an advanced and widely used opensource and free security and IT auditor for physical, virtual and Cloud systems. Its goal is to be usable by an level of user, from IT or Security.
> Its first installment is focused on Azure Entra ID. I am creating $${\color{LimeGreen}Inquisitor}$$ with the goal of building a team of industry leaders to work with me, right now the source code will be restricted to that group until it is ready for release.  Please let us know at Info at Senserva if you want to join with, and we have a great team going already.  I wrote my first Windows NT scanner for 3M Corporation in 1994, shortly after leaving the Windows NT Dev Team in Redmond.  I sold that to George Kurtz and Foundstone. I then wrote the patch system called HFNetChk and MBSA  (working with Microsoft), which is also the root of WSUS.  Of these things help secure millions of computers. I sold that company, Shavlik Technologies, to VMware and soon after started writing scanners for Microsoft Azure, including the Advanced Drift Management in Senserva's main product.

![Clip6](https://github.com/user-attachments/assets/bae008ae-8830-41ab-b739-c61bd454b5c5)

Use $${\color{LimeGreen}Inquisitor}$$ to just look for top issues or drill deep on the state of each Entra ID you manage, the data and interface support both. You can also easily edit the content of the  $${\color{LimeGreen}Inq.exe}$$ user interface or create your own.  We support Microsoft Excel, Json and relational databases. There can be a lot of data if you are running in "Info" mode.  The $${\color{LimeGreen}Inq.exe}$$ scanner is a commandline and can be used stand-alone.   $${\color{LimeGreen}Inq.exe}$$ also provides an extensive set of web page based information for easier review, or you can create your own UI.

* Use Cases
  * Quick security checks, just look for high level issues. 
  * Recurring deep review, dig into the data to look for trends. Replaces need to call APIs or KQL by hand.
  * Conditional Access Rules and Usage - dig deep in to CA, see what rules are used, not used, will never be used and more
  * Replace existing scripts and grab data from the Inquisitor SQL database or generated CSV files
  * Inquisitor can be run over and over, it only records changes so it is very efficent

⭐ Please Star/Follow/Watch us on GitHub — it motivates all of us! And it keeps you informed about changes as well. (Thank you!!)  We also want your input so please files Issues for any questions or input.

> [!IMPORTANT]
> **This is Beta 1, it will return great data, but it may not always be accurate.  We need feedback. Please create Issues for all requests. Thank you - the Senserva Team. **

# ⚡️ $${\color{LimeGreen}Inquisitor}$$ No Installation Needed, Just Run It

Download $${\color{LimeGreen}Inq.exe}$$ to get started, with a double click or a clone, and enter inq.exe . $${\color{LimeGreen}Inq.exe}$$ has a digital signature so your AV should be OK with it. If not please let us know right away.  

You do not have to register, log in or do anything other than review, agree to and follow our [EULA](https://github.com/Senserva-LLC/Senserva-Inquisitor/blob/main/EULA.html). Delete the installation directory and $${\color{LimeGreen}Inq.exe}$$ gone, it only uses the installation directory.

The Senserva $${\color{LimeGreen}Inquisitor}$$ (aka $${\color{LimeGreen}Inq.exe}$$) as many options and ways to work with, but things can come as you learn more about $${\color{LimeGreen}Inq.exe}$$. $${\color{LimeGreen}Inq.exe}$$ installs itself, just run it and the first time it will create the database and browser files it needs in the directory you are running in.  That's it, $${\color{LimeGreen}Inq.exe}$$ will figure things on its own from there. By default $${\color{LimeGreen}Inq.exe}$$ trys various logins automaticly to find the best one for you. Or you can select your login mode with a parameter.

> [!TIP]
> Start with the quick start and take the defaults.  Let $${\color{LimeGreen}Inq.exe}$$ do the initial heavy lifting. Then after a few usages start looking deep into the data. The $${\color{LimeGreen}Inq.exe}$$ data is tagged with levels such as High Risk, or just Informational. You can filter the data in the UI to quickly learn your state.  You can run with any user rights to see what data you get back, but Security Reader or Global Reader work best.


# 🚀 Key $${\color{LimeGreen}Inquisitor}$$ Features
* There are no servers used. No web servers, no database severs. None.  Yet there is a full relational database thanks to SQLite and rich web pages based on html files local to the inq.exe directly to review results. This is done by design, to keep the data local and to keep it simple on the outside but very advance do the inside.
* Just download the Signed Inq.exe and go, setup is complete automated. 
* Each time you run an scan only changes are recorded in the database.  You can run inq.exe all you want and only new data is saved.
* Easy to login to Azure, including Zero setup options.
* It is easy to share data with others. Inq.exe runs in two modes, audit mode which requires an Azure Login and Reporting mode which can be run by anyone.
* Built to be customized. The database and user interface can be easily accessed and customized from multiple platforms to create custom monitors and reports.
* The User interface can export Json with user interface search and filter dials that enable it to be broad or specific data. 
* Output text can be easily customized via auto-generated CSV files that are used to display all key text.
* Full leveled logging to auto-rolling files support, makes it easy to understand what is going on inside Inq.exe.
* Trends stored in the data. $${\color{LimeGreen}Inquisitor}$$ data is deduped and contains a history.  So, it does not grow too large, but at the same time you can observe changes over time.
* Source code available

# Commandline Parameters

![image](https://github.com/user-attachments/assets/4c6265e9-2d33-4f7b-8358-d04a9e7e9595)

# 🌟 $${\color{LimeGreen}Inquisitor}$$ What We Manage

* Extensive Audit and Monitoring
  * Directory Logs
  * Signin Logs
  * Conditional Access Rules and Usage
  * Users
* Basic Audit and Monitoring
  * Service Principals
  * Devices
  * Groups
  * Roles
  * Risky Users
  * Risk Detections
* Next
  * More Audit and Monitoring for Service Principal Audit, Groups Audit, Roles, Risky Users, Risk Detections
  * Add
    * Secure Score Audit and Monitoring
    * Service Principal Risk Detections Audit and Monitoring
    * Risky Service Principals Audit and Monitoring
    * PIM Audit and Monitoring

# 🛠️ How $${\color{LimeGreen}Inquisitor}$$ Works

$${\color{LimeGreen}Inquisitor}$$ runs scans on demand, with scheduling and Containers coming in a future beta.

## Getting Credentials

### There are Many Options for Logging into Azure

$${\color{LimeGreen}Inq.exe}$$ and many options to login in to Azure.  The easiest way to go is to use the Azure CLI and $${\color{LimeGreen}Inq.exe}$$ just uses your current login, you do not need to do anything if you are already using the Azure CLI, or you can easily set it up.  The Azure PowerShell is also supported.

> [!TIP]
> If you are using Azure CLI login with that to start out.  It is easy, you have nothing to do. Over time you may want to create your own Entra ID Client to get all the rights Inq.exe is able to take advanage of.

## How $${\color{LimeGreen}Inquisitor}$$ uses User Rights. TODO

#### The Azure CLI

The best way to start working with $${\color{LimeGreen}Inq.exe}$$. If its already running for you there is nothing to do.  If its not already running its easy to install and login and let Inq.exe take it from there.

The Azure Command-Line Interface (CLI) is a cross-platform command-line tool to connect to Azure and execute administrative commands on Azure resources. It allows the execution of commands through a terminal using interactive command-line prompts or a script. [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/what-is-azure-cli)

#### The Az PowerShell Module

Note Beta 1 is not reliable for this, at  least in our testing. It may work for you as we believe we are calling everything correctly.

The Az PowerShell module is a set of cmdlets for managing Azure resources directly from PowerShell. [The Az PowerShell Module](https://learn.microsoft.com/en-us/powershell/azure/new-azureps-module-az?view=azps-13.0.0)

#### The Senserva Demo EntraID Client

Example, list all rights for the full product

#### Customer EntraID Client

based on Senserva's but make your own. This is an advanced usage and it enables the most features

## $${\color{LimeGreen}Inquisitor}$$ In Action

## Logging

$${\color{LimeGreen}Inquisitor}$$ has detailed logging, stored in the Log subdirectory.  The scan $${\color{LimeGreen}Inquisitor}$$ will show select data so you can easily monitor progress, but all the data on the the UI and much more will be in the logs.  

Logs/SenservaLogFile20250116 is an example log name.  The numbers break out to the year and the day, and the logs have automatic roll over so they stay managable.

A quick review of the logs gives you an indepth review of what $${\color{LimeGreen}Inquisitor}$$ is doing, or the issues may have.

*  ...
*  2025-01-16 11:40:36.307 -06:00 [INF] Senserva.Scanner.AuditManager  Senserva "EntraSigninLogs" AuditCompleted
*  2025-01-16 11:40:36.310 -06:00 [INF] Senserva.Scanner.AuditManager  Senserva "Devices" EnableAudit
*  2025-01-16 11:40:38.795 -06:00 [INF] Senserva.Scanner.AuditManager  Senserva "Devices" AuditCompleted
*  2025-01-16 11:40:38.894 -06:00 [INF] Senserva.Scanner.AuditManager  Senserva "RiskyUsers" EnableAudit
*  2025-01-16 11:41:03.604 -06:00 [ERR] Senserva.Scanner.SenservaGraph  Senserva "SignInPreferences" Request Authorization failed
*  ...

## Working with the Results

There are multiple ways to work with the results from $${\color{LimeGreen}Inquisitor}$$

* Using our advance UI to work with the data, sort it, filter and export it
* Export the data to CSV and us Microsoft Excel to work with the data
* Export Json from the UI and create you own views with your viewing tools
* Directly access the database with your own application, possibly in Python

## Logic and Dataflow

```mermaid

graph TD;
    Login --> read-azure[Read Azure] --> Review-Azure-State[Review Azure State] --> Database[(SQLite)] --> Create-Webpages[Create Inquisitor Webpages];
    Azure-Cli-Client[Azure Cli] -->Login;
    Senserva-EntraID-Client[Senserva Entra Client] -->Login;
    Customer-EntraID-Client[Customer Entra Client] -->Login;
    Powershell-Cli-Client[Azure PowerShell Client] -->Login;
    User-Customized-Strings[Customized Strings] --> CSV-Importer[CSV Importer];
    CSV-Importer --> Database[(SQLite)];
    Create-Webpages --> Json;
    Create-Webpages --> CSV-Excel;
    Create-Webpages --> Browser;
    Database[(SQLite)] --> Custom-Solutions[Custom Solutions];
    Database[(SQLite)] --> CSV-Excel;
    Create-Webpages --> HTML-Files;
style Login fill:#80BC00,color:#000080,font-size:16pt
style Customer-EntraID-Client fill:#46C2CB,color:#000080,font-size:16pt
style Azure-Cli-Client fill:#46C2CB,color:#000080,font-size:16pt
style Senserva-EntraID-Client fill:#46C2CB,color:#000080,font-size:16pt
style Powershell-Cli-Client fill:#46C2CB,color:#000080,font-size:16pt
style CSV-Importer fill:#80BC00,color:#000080,font-size:16pt
style Create-Webpages fill:#80BC00,color:#000080,font-size:16pt
style Database fill:#000080,color:#80BC00,font-size:16pt
style Custom-Solutions fill:#000080,color:#80BC00,font-size:16pt
style Create-Webpages fill:#80BC00,color:#000080,font-size:16pt
style Review-Azure-State fill:#80BC00,color:#000080,font-size:16pt
style read-azure fill:#80BC00,color:#000080,font-size:16pt
style User-Customized-Strings fill:#80BC00,color:#000080,font-size:16pt
style Json fill:#000080,color:#80BC00,font-size:16pt
style CSV-Excel fill:#000080,color:#80BC00,font-size:16pt
style HTML-Files fill:#000080,color:#80BC00,font-size:16pt;
style Exporter fill:#80BC00,color:#000080,font-size:16pt
style Browser fill:#000080,color:#80BC00,font-size:16pt
linkStyle default stroke:#80BC00
```

By default CSV files create are Audit.csv (Clean, reviewed), Nodes.csv (Raw Azure data), Edges.csv (connections between Azure data), ConditionalAccessCounts.csv (usage counts), and SigninCounts.csv (extensive log reviews). Users can create their own custom CSV files via the html file based user interface. This data is the same data that is in the database, it is just presented this way so it can be viewed in things like Microsoft Excel.

# $${\color{LimeGreen}Inquisitor}$$ Database

The Senserva $${\color{LimeGreen}Inquisitor}$$ uses a relational database to store results. You can 100% ignore the database if you wish, or you can dig in an create your own reporting.  The data model is basic and after a few runs of Inq.exe it will make sense to you.

> [!NOTE]
> Digging into the Senserva $${\color{LimeGreen}Inq.exe}$$ database is for advanced users who want to create their own front-end to the data, something we encourage as long as license rights are followed.  But - at the same time - we have a great customizable UI out of the box, start there.  You can edit the text via published CSV files if you wish.

## ⚙️ $${\color{LimeGreen}Inquisitor}$$ Integrations

$${\color{LimeGreen}Inquisitor}$$ is built with SQLite. SQLite is a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world. [More About Sqlite](https://www.sqlite.org/)

It is easy to work with SQLite in Python and other languages. The Python SQLite3 module is used to integrate the SQLite database with Python. There is no need to install this module separately as it comes along with Python after the 2.5x version. [More About Python and Sqlite](https://docs.python.org/3/library/sqlite3.html) 

SQLite can also be used with PowerShell to read Inq.Uisitor data.  [SQLite and PowerShell with SimplySql](https://www.powershellgallery.com/packages/SimplySql/2.0.2.70)

# Easily Extend $${\color{LimeGreen}Inquisitor}$$

## $${\color{LimeGreen}Inquisitor}$$ in Excel

TODO

## $${\color{LimeGreen}Inquisitor}$$ Json Design

TODO show enough Json here to let people know what we do

## $${\color{LimeGreen}Inquisitor}$$ Database Design

This is an quick overview of the main data tables used by Senserva to go give you an idea of the extent of our data.  Use a product like [DB Browser for SQLite](https://sqlitebrowser.org/) to full review the data format and content.  Or contact us we are glad to help.  Our data model is simple and the data is rich, take a peek behind the scenes with the DB Browsers when you get a minute.

You do not need to know the database to run $${\color{LimeGreen}Inq.exe}$$.  These notes are for people who want to create their own customizations. Our tables also contain rich set of Json data as well so is a lot of data you can use to create custom solutions.  Or you can just use our UI, it is pretty good :)

```mermaid

classDiagram
   
    AuditHistory <|-- Node
    AuditHistory <|-- Edge
    AuditHistory <|-- AuditItem
    AuditHistory <|-- ConditionalAccessCounts
    AuditHistory <|-- CountTrackers
    AuditHistory <|-- AuditAttributes
    Node <|-- Edge

     class AuditHistory["Audit History"]:::someclass {
           TenantId
           AuditId
           StartedTime
           Ended
     }
 style AuditHistory fill:#80BC00,color:#000080,font-size:16pt

      class Node{ 
         Timestamp
         TenantId
         AuditId
         SystemId
         Name
         DataDeleted
         DataCreated
         DataUpdated
         Json
    }
 style Node fill:#80BC00,color:#000080

   class Edge { 
         Timestamp
         TenantId
         AuditId
         DeletedTime
         SourceId
         SourceName
         TargetId
         TargetName
         TargetSubId
   }
 style Edge fill:#80BC00,color:#000080,font-size:16pt

  class AuditItem["Audit Item"] {
  TenantId
  AuditId
  TenantName
  AuditGroup
  AuditType
  ResultDetails
  Risk
  TimeOfOccurance
  SystemId
  SystemName
  SystemId2
  SystemName2
  UserId
  UserName
  Status
  Json
 }
 style AuditItem fill:#80BC00,color:#000080,font-size:16pt

    class ConditionalAccessCounts["Conditional Access Counts"]{
         Timestamp
         TenantId
         AuditId
         ValueType
         PolicyId
         PolicyName
         UserId
         UserName
         Key
         Count
    }
 style ConditionalAccessCounts fill:#80BC00,color:#000080,font-size:16pt

class CountTrackers["Count Trackers"]{
                        Timestamp 
                        TenantId
                        AuditId
                        TenantName
                        CountType
                        Id
                        Name
                        Count
                   }
 style CountTrackers fill:#80BC00,color:#000080,font-size:16pt

  class AuditAttributes["Audit Attributes"] {
                        Timestamp
                        Name
                        Version
                        Description
                        RecommendedRisk
                        Enabled
                        InBeta
                        Ranking
                        Url
                        Nist
                        Mitre
                        Other
                        Credit
                        }
      
 style AuditAttributes fill:#80BC00,color:#000080,font-size:16pt

```

> [!CAUTION]
> Please note that while sharing of Senserva output data easy to do since its in external files, it is important to handle Senserva data with care. Ensure you verify the recipient's identity and always use secure methods for sharing the information.
> 
# Changing Content with the $${\color{LimeGreen}Inq.exe}$$ CSV file

Senserva provides an Excel Compliant file that you can easily edit to control output text.  The file is created after the first run of Inq.exe (the first run includes the install phase). So to use this CSV data just run 2 scans, the 2nd one is fast because we only look for changes since the last scan.      [Checks](https://github.com/Senserva-LLC/Senserva-Inquisitor/blob/main/Senserva.csv)                               

## Web Pages

# $${\color{LimeGreen}Inquisitor}$$ Project Status
Runtimes for Senserva - early beta please contact us for assistance and information. Senserva provides public contains with significant support, and then we add more for partners and customers who work more closely with us. All for free. Source could available to select partners and customers, please check with us.

## ${\color{LimeGreen}Inquisitor}$$ Known Bugs

## 🗺 ${\color{LimeGreen}Inquisitor}$$ Roadmap

* Scheduling
* Remediation
* Containers
* Powershell cmdlets 
* Drift Managent
* Patch Management
    
##❓${\color{LimeGreen}Inquisitor}$$ FAQ


# Beta 1 Release Notes

# Recommendations

Senserva supports many types of login techniques, but the easiest way to get start is with the Azure Cli. [https://github.com/MicrosoftDocs/azure-docs-cli/blob/main/docs-ref-conceptual/install-azure-cli-windows.md](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli) or https://learn.microsoft.com/en-us/dotnet/azure/install-azure-cli 

# 📄 $${\color{LimeGreen}Inq.exe}$$ License
Please review the SenservaLicense file before using this software. And note These run times only for END USER USE ONLY. They cannot be used within other products or be embedded in paid services without Senserva's express written permission. Senserva has an established OEM program with a scalable pricing model that works for companies of all sizes.  Please contact us for use of these, and all our works, as part of your products or to be embedded in your services. Also be sure to read the text around PROVIDED "AS IS" AND WITH ALL FAULTS AND DEFECTS WITHOUT WARRANTY OF ANY KIND.

Please note these run times are not yet ready for use, we are testing out the builds etc.

# 🤝 Contributing

Senserva is growing quickly and we would love more people to get involved in this project. Whether you have ideas to share, bugs to report, or features  you want to see, your contributions are welcome!

# 💡About Senserva

The Senserva team is built with a team Microsoft Security Industry leaders including former Microsoft employees. Senserva believes an essential component of computer security is the efficient application of security tools and automated processes.

We provide straightforward, continuous, and actionable insights into what needs the most immediate attention. Creating guidance on the proper use of Microsoft and other security products for all levels of security skills and driving the management of those insights.

Senserva, an ISV member of the exclusive Microsoft Intelligent Security Association (MISA) and 2024 ISV of the year finalist, was founded by industry leader and Microsoft Security expert, Mark Shavlik, along with TJ Dolan.

 [More About Senserva](https://senserva.com/about)
 










