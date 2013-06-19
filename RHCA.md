# Introduction

This is the big one chaps

Requires passing:

- Red Hat Enterprise Security: Network Services Expertise Exam (EX333)
- Red Hat Enterprise Deployment and Systems Management Expertise Exam (EX401)
- Red Hat Enterprise Clustering and Storage Management Expertise Exam (EX436)
- Red Hat Enterprise System Monitoring and Performance Tuning Expertise Exam (EX442)

Plus either

- (Alt. 1) Red Hat Enterprise Directory Services and Authentication Expertise Exam (EX423)

or

- (Alt. 2) Red Hat Enterprise Virtualization (RHCVA) Exam (EX318)

# Security: Network Services Expertise

## Course outline
 
    Internet threat model and the attacker's plan
    System security and service availability
    An overview of protection mechanisms

### Basic service security

    SELinux
    Host-based access control
    Firewalls using Netfilter and iptables
    TCP wrappers
    xinetd and service limits

###Cryptography

    Overview of cryptographic techniques
    Management of SSL certificates
    Using GnuPG

###Logging and NTP

    Time synchronization with NTP
    Logging: syslog and its weaknesses
    Protecting log servers

###BIND and DNS security

    BIND vulnerabilities
    DNS security: attacks on DNS
    Access control lists
    Transaction signatures
    Restricting zone transfers and recursive queries
    DNS topologies
    Bogus servers and black holes
    Views
    Monitoring and logging
    Dynamic DNS security

###Network authentication: RPC, NIS, and Kerberos

    Vulnerabilities
    Network-managed users and account management
    RPC and NIS security issues
    Improving NIS security
    Using Kerberos authentication
    Debugging Kerberized services
    Kerberos cross-realm trust
    Kerberos encryption

###Network File System

    Overview of NFS versions 2, 3, and 4
    Security in NFS versions 2 and 3
    Improvements in security in NFS4
    Troubleshooting NFS4
    Client-side mount options

###OpenSSH

    Vulnerabilities
    Server configuration and the SSH protocols
    Authentication and access control
    Client-side security
    Protecting private keys
    Port-forwarding and X11-forwarding issues

###Electronic mail with Sendmail

    Vulnerabilities
    Server topologies
    Email encryption
    Access control and STARTTLS
    Anti-spam mechanisms

###Postfix

    Vulnerabilities
    Security and Postfix design
    Configuring SASL/TLS

###FTP

    Vulnerabilities
    The FTP protocol and FTP servers
    Logging
    Anonymous FTP
    Access control

###Apache security

    Vulnerabilities
    Access control
    Authentication: files, passwords, Kerberos
    Security implications of common configuration options
    CGI security
    Server-side includes
    suEXEC

###Intrusion detection and recovery

    Intrusion risks
    Security policy
    Detecting possible intrusions
    Monitoring network traffic and open ports
    Detecting modified files
    Investigating and verifying detected intrusions
    Recovering from, reporting, and documenting intrusions


##Exam Objectives:
###  Centralized authentication security

    Configure an NIS server to provide directory services.

    Configure Kerberos to provide user authentication.

    Configure NFSv4 server.

    Configure a network client to use NIS for directory information.

    Configure a network client to use Kerberos for authentication.

    Configure a network client to mount an NFSv4 export.

    Configure r-clients (rlogin, rcp, etc.) and telnet to use Kerberos.

### Network Services Security

    Use xinetd and TCP wrappers to restrict access to network services.

    Configure Postfix and Sendmail to:

        Filter mail based on message characteristics.

        Use TLS for secure communication.

        Use the Real-time Blackhole List (RBL) via DNS.

    Configure POP/IMAP to use SSL/TLS for secure communication.

    Configure the following aspects of DNS:

        Master domain

        Slave domain

        Views

        Forwarders

        Blackhole lists (RBL)

        TSIG

    Use GPG tools to:

        Generate key pairs.

        Sign documents.

        Encrypt documents.

        Decrypt documents.

        Verify document signatures.

        Configure a certificate authority (CA) and sign certificate requests.

    Configure httpd to use an SSL certificate signed by a certifying authority.

    Configure httpd to use passwords and/or network location to restrict access to content.

    Configure FTP security to:

        Support FTP only users.

        Implement host-based access restrictions.


# Deployment and Systems Management

    SELinux policy administration
    
    Install, configure, and use Red Hat Network Satellite server.

    Install an RHN Satellite server.

    Add base channels from ISO images.

    Create child channels of a base channel.

    Create different types of users.

    Create groups and add group admins.

    Create configuration channels.

    Create a custom RPM spec file and build a binary RPM from source code.

    Upload custom RPMS to an RHN Satellite server.

    Create Activation keys.

    Assign groups, software channels, and configuration channels to the Activation key.

    Configure errata.

    Provision clients using kickstart.

    Set up and configure DHCP.

    Configure PXE-boot.

    Set up an SVN version control repository.

    Kickstart a machine using Cobbler.

    Manage virtual systems using Red Hat Network Satellite server.

    Clone channels and use a cloned channel.


# Clustering and Storage Management 

## Course overview

Get an overview of storage and cluster technologies.
ISCSI configuration

Set up and manage iSCSI.
UDEV

Learn basic manipulation and creation of udev rules.
Multipathing

Combine multiple paths to SAN devices into one fault-tolerant virtual device.
Red Hat high-availability overview

Learn the architecture and component technologies in the Red Hat® High Availability Add-On.
Quorum

Understand quorum and quorum calculations.
Fencing

Understand Fencing and fencing configuration.
Resources and resource groups

Understand rgmanager and the configuration of resources and resource groups.
Advanced resource management

Understand resource dependencies and complex resources.
Two-node cluster issues

Understand the use and limitations of 2-node clusters.
LVM management

Review LVM commands and Clustered LVM (clvm).
Global File System 2

Understand the GFS2 file system and use tools to create, maintain, and troubleshoot it.
XFS

Explore the Features of the XFS® file system and tools required for creating, maintaining, and troubleshooting.
Red Hat Storage

Work with Gluster to create and maintain a scale-out storage solution.
Comprehensive review


## Exam Objectives
Set up high-availability services and storage.

    Configure a high-availability cluster, using either physical or virtual systems, that:
        Provides a service fail-over between the nodes.
        Provides a preferred node for the service.
        Selectively fails over based on node characteristics.
    Manage logical volumes in a clustered environment such as:
        Create volumes and volume groups that are available to all members of a highly-available cluster
        Create snapshots of logical volumes
    Configure a GFS file system to:
        Meet specified size, layout, and performance objectives.
        Support file system quotas.
    Configure iSCSI targets and initiators.
    Manage device configuration using udev
    Create and manage Red Hat Storage based clusters including:
        Creating distributed clusters
        Creating replicated clusters
        Implementing and utilizing appropriate file systems

# System Monitoring and Performance Tuning
## Couse Outline
 Introduction to performance tuning

Understand the basic principles of performance tuning and analysis.
Collecting, graphing, and interpreting data

Gain proficiency in using basic analysis tools and in evaluating data.
General tuning

Learn basic tuning theory and mechanisms used to tune the system.
Hardware profiling

Understand and analyze hardware.
Software profiling

Analyze CPU and memory performance of applications.
Mail server tuning

Learn about basic storage tuning using an email server as an example.
Large memory workload tuning

Understand memory management and tuning.
HPC workload tuning

Understand tuning for CPU-bound applications.
File server tuning

Understand storage and network tuning in the context of a file server application.
Database server tuning

Tune memory and network performance using a database application as an example.
Power usage tuning

Tune systems with power consumption in mind.
Virtualization tuning

Tune ’host’ and ’guest’ for efficient virtualization.

## Exam Objectives
    use utilities such as vmstat,iostat,mpstat,sar, gnome-system-monitor, top, powertop and others to analyze and report system and application behavior

    configure systems to provide performance metrics using utilities such as RRDtool

    use the Pluggable Authentication Modules (PAM) mechanism to implement restrictions on critical system resources

    use /proc/sys, sysctl and /sys to examine and modify and set kernel run-time parameters

    use utilities such as dmesg, dmidecode, x86info, sosreport etc. to profile system hardware configurations

    analyze system and application behavior using tools such as ps, strace, top and Valgrind

    configure systems to run SystemTap scripts

    alter process priorities of both new and existing processes

    configure systems to support alternate page sizes for applications that use large amounts of memory

    given multiple versions of applications that perform the same or similar tasks, choose which version of the application to run on a system based on its observed performance characteristics

    configure disk subsystems for optimal performance using mechanisms such as swap partition placement, I/O scheduling algorithm selection, file system layout and others

    configure kernel behavior by altering module parameters

    calculate network buffer sizes based on known quantities such as bandwidth and round-trip time and set system buffer sizes based on those calculations

    select and configure tuned profiles.

    manage system resource usage using control groups


# Directory Services and Authentication
## Course Outline
 Introduction to directory services

    What is a directory?

    LDAP: models, schema, and attributes

    Object classes

    LDIF

The LDAP naming model

    Directory information trees and Distinguished Names

    X.500 and "Internet" naming suffixes

    Planning the directory hierarchy

Red Hat Directory Server: basic configuration

    Installation and setup of Red Hat® Directory Server

    Using the Red Hat console

    Using logging to monitor Red Hat Directory Server activity

    Backing up and restoring the directory

    Basic performance tuning with indexes

Searching and modifying the LDAP directory

    Using command-line utilities to search the directory

    Search filter syntax

    Updating the directory

Red Hat Directory Server: authentication and security

    Configuring TLS security

    Using access control instructions (ACIs)

    ACIs and the Red Hat console

Linux user authentication with NSS and PAM

    Understanding authentication and authorization

    Name service switch (NSS)

    Advanced pluggable authentication modules (PAM) configuration

Centralized user authentication with LDAP

    Central account management with LDAP

    Using migration scripts to migrate existing data into an LDAP server

    LDAP user authentication

Kerberos and LDAP

    Introduction to Kerberos

    Configuring the Kerberos key distribution center (KDC) and clients

    Configuring LDAP to support Kerberos

Directory referrals and replication

    Referrals and replication

    Single master configuration

    Multiple master configuration

    Planning for directory server availability

Cross-platform centralized identity management

    Synchronizing Red Hat Directory Server with Active Directory

    Managing users with Winbind and LDAP

    Mapping attributes between Linux® and Microsoft Windows

## Exam Objectives


    Install Red Hat Directory Server.

    Configure the default lightweight directory access protocol (LDAP) suffix.

    Configure the administrative user.

    Configure a slave replica.

    Configure Red Hat Directory Server for transport layer security (TLS) communication.

    Request a certificate from a certificate authority (CA).

    Install CA-signed server certificate.

    Configure command-line tools.

    Use TLS.

    Use a default LDAP suffix.

    Configure Red Hat Directory Server access through user access controls.

    Authenticate to the Directory Server using kerberos.

    Configure write referrals.

    Migrate NIS users and groups into LDAP.

    Create and modify entries of the inetOrgPerson object class.

    Import user information from an LDIF file.

    Export specific user information to an LDIF file.

    Configure a system to authenticate using LDAP.

    Configure a system to authenticate using Active Directory.

# Enterprise Virtualization

## Course Outline
 Red Hat Enterprise Virtualization overview
Understand general virtualization, KVM concepts, and Red Hat® Enterprise Virtualization platform.

Red Hat Enterprise Virtualization Manager
Install, test, remove, and troubleshoot Red Hat Enterprise Virtualization Manager.

Red Hat Enterprise Virtualization Hypervisor
Install, configure, upgrade, and troubleshoot Red Hat Enterprise Virtualization Hypervisor.

Red Hat Enterprise Virtualization environment configuration
Create and configure datacenters, clusters, storage domains, and logical networks.

Red Hat Enterprise Virtualization for Servers
Install, perform basic management of, and troubleshoot virtual servers and images.

Red Hat Enterprise Virtualization for Desktops
Install virtual desktops and configure paravirtualized drivers.

Virtual machine templates
Create Microsoft Windows and Red Hat Enterprise Linux® virtual machines with template images.

Pools and users
Use pools and deploy the user portal with multilevel administrative roles.

Monitoring and reports
Monitor Red Hat Enterprise Virtualization and create custom reports.

Advanced Red Hat Enterprise Virtualization
Back up and restore Red Hat Enterprise Virtualization; CLI and API interfaces.

Red Hat Enterprise Linux hosts
Manage virtual machines with Red Hat Network.

Migration and high availability
Migrate a virtual machine and explore high availability

## Exam Objectives


    Install Red Hat Enterprise Virtualization Manager and any dependencies.

    Use Red Hat Enterprise Virtualization Manager to:

        Create datacenters and clusters.

        Manage hypervisor hosts.

        Configure storage.

        Create Red Hat Enterprise Linux and Microsoft Windows virtual machines.

        Develop pools and templates.

        Set up Red Hat Enterprise Virtualization Manager users.

    Install and configure a Red Hat Virtualization Hypervisor to support guests and attach to a Red Hat Enterprise Virtualization Manager.

    Import installation media for creating new virtual machines.

    Perform management tasks, such as collecting logs, creating bookmarks for specific events, and more.

