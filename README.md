
[![apm](https://img.shields.io/apm/l/vim-mode.svg)](https://github.com/LowlyDBA/ExpressSQL/) [![Sample Data For Change](https://img.shields.io/badge/Sample%20Data%20For%20Change-%E2%9D%A4-red)][sdfc] 

# Table of Contents

* [Instance](#instance)
  * [Database](#database)
    * [Database User](#database-user)
  * [Management](#management)
    * [Policy Management](#policy-management)
  * [SQL Server Agent](#sql-server-agent)
    * [Job](#job)
  * [Security](#security)
    * [Login](#login)
    * [Server Role](#server-role)
* [Why these samples](#why-these-samples)
* [Contribute](#contribute)

*Icons are from version 18 or greater.*

## Instance

Indicates the status of the SQL Server instance.

| Icon | Description |
| ---- | ----------- |
| ![Instance running](assets/instance_running.png) | SQL Server instance service state is running. |
| ![Instance unknown](assets/instance_unknown.png) | SQL Server instance service state is unknown and cannot be reached. |

## Database

Indicates the status of the database.

| Icon | Description |
| ---- | ----------- |
| ![Database normal](assets/db_normal.png) | Database state is normal. |
| ![Database offline](assets/db_offline.png) | Database state is offline. |
| ![Database restoring](assets/db_restoring.png) | Database state is restoring. |
| ![Database recovery](assets/db_recoverypending.png) | Database state is pending recovery. |
| ![Database suspect](assets/db_suspect.png) | Database state is suspect. |

### Database User

| Icon | Description |
| ---- | ----------- |
| ![Dbuser enabled](assets/dbuser_enabled.png) | Database user state is enabled - user granted connect privileges. |
| ![Dbuser disabled](assets/dbuser_disabled.png) | Database user state is disabled - user denied connect privileges. |

## Management

### Policy Management

Indicates the status of policy management.

| Icon | Description |
| ---- | ----------- |
| ![PolicyMgmt enabled](assets/policymgmt_enabled.png) | Policy Management state is enabled. |
| ![PolicyMgmt disabled](assets/policymgmt_disabled.png) | Policy Management state is disabled or unavailable in this edition. |

### Resource Governor

| Icon | Description |
| ---- | ----------- |
| ![ResourceGov enabled](assets/resourcegov_enabled.png) | Resource Governor state is enabled. |
| ![ResourceGov disabled](assets/resourcegov_disabled.png) | Resource Governor state is disabled. |

## SQL Server Agent

Indicates the status of the SQL Server Agent service.

| Icon | Description |
| ---- | ----------- |
| ![Agent enabled](assets/agent_enabled.png) | SQL Server Agent service state is running. |
| ![Agent disabled](assets/agent_disabled.png) | SQL Server Agent service is not running. |
| ![Agent unknown](assets/agent_unknown.png) | SQL Server Agent service state is unknown and cannot be reached. |

### Job

Indicates the status of the SQL Server Agent job.

| Icon | Description |
| ---- | ----------- |
| ![Job enabled](assets/job_enabled.png) | Job state is enabled. |
| ![Job disabled](assets/job_disabled.png) | Job state is disabled. |

## Security

### Login

Indicates the status of a login.

| Icon | Description |
| ---- | ----------- |
| ![Login enabled](assets/login_enabled.png) | Login state is enabled. |
| ![Login disabled](assets/login_disabled.png) | Login state is disabled. |

### Server Role

Indicates the modification status of a server role.

| Icon | Description |
| ---- | ----------- |
| ![ServerRole unlocked](assets/serverrole_unlocked.png) | Server role state is unlocked and can be modified. |
| ![ServerRole locked](assets/serverrole_locked.png) | Server role state is locked and cannot be modified. |

---

## Why These Samples

The samples chosen for this reference guide were done so as a part of [Sample Data for Change][samps], which strives
to leverage technical examples to increase awareness, diversification, and change within technical fields.

## Contribute

Missing something? Want to add an icon? Open an [issue][issue] to get some :heart:.

[issue]: https://github.com/LowlyDBA/ssms-icon-ref/issues
[samps]: https://lowlydba.github.io/sampledataforchange/
[sdfc]: https://sampledataforchange.github.io/
