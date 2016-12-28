# Multi-level Security and Multi-category Security
The Multi-Level Security technology refers to a security scheme that enforces the Bell-La Padula Mandatory Access Model. Under MLS, users and processes are called subjects, and files, devices, and other passive components of the system are called objects. Both subjects and objects are labeled with a security level, which entails a subject's clearance or an object's classification. Each security level is composed of a sensitivity and a category.
Multi-Category Security (MCS) is an enhancement to SELinux, and allows users to label files with categories. These categories are used to further constrain Discretionary Access Control (DAC) and Type Enforcement (TE) logic. They may also be used when displaying or printing files. An example of a category is "Company_Confidential". Only users with access to this category can access files labeled with the category, assuming the existing DAC and TE rules also permit access.

Implement and demonstrate MLS and MCS security modules in CentOS server. 
Build a factitious enterprise with various department and sensitivity level. i.eHR (s0:c1), Finance(s1:c1), IT(s1:c0,c1023) and Intel(s0-s15:c0,c1023)
Configure and demonstrate the use of MLS and MCS security policy under "Enforcing" in Selinux. 

