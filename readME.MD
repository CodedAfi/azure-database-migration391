# Azure Database Migration Project - Personal Journey

## Introduction

Welcome to my Azure Database Migration Project repository. In this space, I've chronicled my journey through the process of migrating an on-premise SQL database to Azure SQL Database. This project was significant for me as it allowed me to solidify my understanding of cloud environments, database management, and Azure's robust data services. I've documented each step I took, sharing my experiences and the lessons I learned along the way.

## Project Significance

The migration of databases to the cloud is a transformative step for any organization, aiming to leverage the scalability, performance, and security of cloud computing. This project was particularly significant as it was a comprehensive exercise in planning, executing, and validating a database migration process while ensuring minimal downtime and data integrity.

## Milestones & Tasks

### Milestone 1: Set up the Environment

#### Task 1: Set up GitHub
I initiated my project by setting up a GitHub repository to version control my scripts and documentation. This ensured that any changes I made were tracked and could be rolled back if necessary.

#### Task 2: Set up Azure
Next, I set up my Azure environment. This involved creating a subscription, setting up a resource group, and familiarizing myself with the Azure portal.

### Milestone 2: Set up the Production Environment

#### Task 1 to 5
From provisioning a Windows Virtual Machine to installing SQL Server and SQL Server Management Studio (SSMS), I laid down the foundation of my production environment. Creating the production database was a pivotal moment, as it was the database that would eventually be migrated to Azure.

### Milestone 3: Migrate to Azure SQL Database

#### Task 1 to 7
This milestone was the core of the project. I meticulously prepared for migration, ensuring that the schema and data were compatible with Azure SQL Database. The steps I took included setting up the Azure SQL Database, preparing for migration, and executing the schema and data migration. I learned how to use Azure Data Studio and validated the migration success, which was a triumphant moment in the project.

### Milestone 4: Data Backup and Restore

#### Task 1 to 4
I learned the importance of backups firsthand by backing up the on-premise database and restoring it in a development environment. Automating backups taught me about the necessity of regular backup schedules in safeguarding data.

### Milestone 5: Disaster Recovery Simulation

#### Task 1 and 2
Simulating a data loss event was both thrilling and terrifying. I deliberately removed critical data and then used my backup to restore the production database. This exercise showed me the importance of disaster recovery planning.

### Milestone 6: Geo Replication and Failover

#### Task 1 and 2
Here, I configured geo-replication and tested failover to understand how Azure handles data redundancy and availability across geographical locations. It was fascinating to see how data could be synchronized across regions and how failovers could be managed.

### Milestone 7: Microsoft Entra Directory Integration

#### Task 1 and 2
Finally, I configured Microsoft Entra Directory Integration for Azure SQL Database. Creating a read-only user was an essential step in maintaining data security and integrity.

## Conclusion

Reflecting on this project, I've gained not just technical skills but also an appreciation for the strategic planning involved in migrating to the cloud. Each milestone brought its own challenges and learnings, and I feel more confident in my ability to manage and migrate databases within Azure. The significance of this project goes beyond the technical realm; it represents a shift in thinking towards more resilient, scalable, and future-proof database management practices.

I hope that my documented journey will help others embarking on similar projects. If you have any questions, feedback, or need guidance, feel free to reach out or contribute to this repository.

