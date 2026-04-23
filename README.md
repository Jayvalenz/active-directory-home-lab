# active-directory-home-lab
Windows Server lab with AD DS, DNS, DHCP, and File Services using a Marvel-themed domain structure
# Marvel-Themed Active Directory Lab (AD DS + DNS + DHCP)

## 1. Overview
This project is a Windows Server home lab built to simulate a small enterprise environment using Active Directory, DNS, DHCP, and File Services.

The lab uses a Marvel-themed structure (Avengers, X-Men, Fantastic Four) to represent organizational units, users, and security groups.

---

## 2. Environment Architecture

### Servers
- Server 1: Domain Controller (AD DS, DNS)
- Server 2: DHCP Server
- Server 3: File Server

### Client
- Windows 10 machine joined to the domain

### Virtualization
- VMware Workstation Pro 17.5

---

## 3. Active Directory Design

### Organizational Units
- Avengers
- X-Men
- Fantastic Four

### Users
- Thor Odinson/todinson26S
- Tony Stark/tstark26S
- Bruce Banner/bbanner26S
- James Howlett/jhowlett26S
- Ororo Munroe/omunroe26S
- Jean Grey/jgrey26S
- Johnny Storm/jstorm26S
- Sue Storm/jstorm26S
- Reed Richards/rrichards26S

### Groups
- G_Avengers26S
- G_Xmen26S
- G_Fantastic426S

---

## 4. Services Configured

### Active Directory
- Domain Controller configured
- Organizational Units created
- Users and groups assigned

### DNS
- Domain-based name resolution configured
- Integrated with Active Directory

### DHCP
- DHCP scope configured on Server 2
- Clients automatically assigned IP addresses

### File Services
- Shared folders created on Server 3
- Folder redirection configured for users

---

## 5. Screenshots

### Organizational Units
![OUs](screenshots/organizational-units.png)

### Users
![Users](screenshots/users-avengers-xmen.png)

### Groups
![Groups](screenshots/groups-security.png)

### DHCP Scope
![DHCP](screenshots/server2-dhcp-scope.png)

### Client IP Configuration
![IPConfig](screenshots/windows10-ipconfig.png)

### File Shares
![Shares](screenshots/server3-file-shares.png)

### Folder Redirection
![Folder Redirection](screenshots/folder-redirection.png)

---

## 6. Skills Demonstrated
- Active Directory administration
- DNS configuration and integration
- DHCP scope configuration and leasing
- File server and shared folder management
- Folder redirection
- Multi-server environment deployment

---

## 7. Key Takeaways
- DNS is critical for Active Directory functionality
- DHCP simplifies client configuration
- Organizational structure improves access control
- File services and folder redirection centralize data management

---

## 8. Future Improvements
- Add Group Policy Objects (GPOs)
- Add PowerShell automation
- Add SIEM for monitoring
- Add security auditing (login tracking)
