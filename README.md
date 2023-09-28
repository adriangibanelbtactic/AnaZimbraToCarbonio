# Z2Z (Zimbra2Zimbra Migration Tool) -_Version 1.0.2_ -Maintained by BKTECH <http://www.bktech.com.br>
 
# Copyright (C) 2016-2021 Fabio Soares Schmidt <fabio@respirandolinux.com.br>

# DISTRIBUTED UNDER THE CREATIVE COMMONS LICENSE: Attribution-NonCommercial-ShareAlike (CC BY-NC-SA)

This license allows others to remix, tweak, and build upon the original work non-commercially, as long as they attribute
to the CREATOR due credit (original banner and Copyright), and that they license new creations under the SAME terms. This program is
distributed in the hope that it may be useful, but WITHOUT ANY WARRANTY; without an implied warranty of FITNESS for any MARKET or
PARTICULAR APPLICATION.
 
################################################ ################################################ ############################
 
# Contact:
 
 Website: <http://www.bktech.com.br>
Email: <z2z@bktech.com.br>
 
 Developer: Fabio Soares Schmidt <fabio@respirandolinux.com.br> or <https://respirandolinux.com.br>

################################################ ################################################ ############################

[README -v1.0.3]


# CHANGELOG:

 (PLEASE READ THE CHANGELOG FILE)

# INSTALLATION
 
 (PLEASE READ THE INSTALL FILE)
 
# USE
 
 (PLEASE READ THE INSTALL FILE)
  
#Z2Z
This tool was created to facilitate the migration process between Zimbra environments, regardless of which version
or edition is being **used**. Motivated by the challenges encountered in migrations carried out by BKTECH (official Zimbra partner for business and training), in addition to participation in Zimbra communities, the tool aims, in the course of its evolution, to meet the most diverse scenarios, also including migration from other platforms , free and proprietary -"A2Z: Anything/Anywhere to Zimbra".
**In cases of Upgrade, that is, migrating TO a newer version of Zimbra. Operation is not guaranteed in cases of downgrade.**

# WHAT WILL BE MIGRATED?

Although Zimbra is a very advanced tool in terms of migration utilities, the tool speeds up and simplifies the process by exporting:

**(Allowing you to rename the server name during export)**.

[x] Classes of service
[x] Accounts -Preserving passwords, if using internal authentication

[x] Alternative names

[x] Distribution lists

[x] Mailboxes (emails, calendars, tasks, contacts, folders, preferences, etc...)

In this first version, Z2Z facilitates the process of exporting the aforementioned entries, in addition to creating the batch of accounts that must be exported, using the native command -zmmailbox. **Domains must be previously created before importing.**
![alt tag](https://respirandolinux.files.wordpress.com/2017/02/zimbrazimbratmp333z2z-master.jpg) 

# DEPOIMENTOS
"We recently used the **Z2Z**tool at the Regional Labor Court of the 13th Region to support the migration of 2400 accounts. This tool was very useful as we were on a very old version of Zimbra, which made it impossible to update via script. The migration It happened incrementally due to the number of accounts until the switch. Everything went as expected and today we are using the most current version of Zimbra." -Filipe A. Motta Braga -Regional Labor Court of the 13th. Region -Paraíba
"I would like to congratulate you on the excellent z2z tool, it helped me a lot in a migration from Zimbra 8.0.7 to 8.7.11
Big hug!" -Marco Brandão -Plus Informática -Minas Gerais
"Congratulations on this excellent tool, it would be impossible to migrate our company's old server without the help of your project. The import was perfect, almost 160 accounts with more than 700GB of data, no failures and a fast and stable environment after the import. " -Alisson S. Conde – IT Team Paranatex Têxtil LTDA -Paraná
"I used Z2Z to migrate two Zimbra servers (8.8.11 > 8.8.12). And my experience with the tool was the best possible, everything went as expected, without any errors. Some time ago I had to do the same job, as I didn't know the tool yet, we tried using Zimbra itself, but we had a lot of errors with boxes over 2GB, so we did it using other methods. This cost us almost 3 days of work. With Z2Z, we were able to do the same job in just one day and no headaches. Thanks Fábio for the excellent work." -Fernando Lima, Gobah! IT Solutions -Goiás.
# ROADMAP
 
In future versions, the tool aims to address scenarios with Multi-Server environments that involve replacing mailbox server hostnames, in addition to exporting the main configurations of the Zimbra environment.

The treatment of different migration strategies is also part of its evolution plan, allowing gradual migrations, for example, through incremental export and import processes.
**ALL evaluation and contribution _(coding, testing, criticism, suggestions)_ is very welcome!**
 
Thank you in advance for your attention.
