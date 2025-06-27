# Cybersecurity Internship Task 4: Firewall Setup

## Author
- **Name**: Neel Bhatt  
- **Date**: June 27, 2025  
- **Repository**: Cybersecurity-Task4

## Objective
Configure and test basic firewall rules to allow or block traffic on Kali Linux.

## Tools Used
- **UFW (Uncomplicated Firewall)**: Installed and configured for managing firewall rules after resolving repository issues.

## Steps Performed
1. Added the Kali archive key and updated the package repositories to fix GPG errors.
2. Installed UFW and enabled it on the system.
3. Checked the initial firewall status and listed existing rules.
4. Added a rule to block inbound traffic on port 23 (Telnet) and tested it.
5. Added a rule to allow inbound traffic on port 22 (SSH) and verified.
6. Removed the test block rule to restore the original firewall state.
7. Documented all commands and created a detailed report.

## Files Included
- `firewall_commands.txt`: A well-organized list of UFW commands executed.
- `vulnerability_report.txt`: A comprehensive report on firewall configuration and traffic filtering.

## Key Learnings
- Gained skills in troubleshooting repository and GPG key issues.
- Mastered the configuration of UFW to block and allow specific ports.
- Developed an understanding of how firewalls enhance network security through traffic filtering.

## Challenges
- Encountered `apt-key` deprecation and repository errors; resolved using modern key management techniques.

## Acknowledgments
- **Elevate Cybersecurity Internship**: For providing this valuable learning opportunity.
- **Neel Bhatt**: For successfully completing the firewall setup under the given constraints.

This repository represents my work for Task 4, submitted with full adherence to ethical guidelines and permission.
