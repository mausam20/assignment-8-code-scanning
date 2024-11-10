# Answers to Assignment 8 Part 3

Add your answers to the questions in Assignment 8 Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
    pkg:pypi/pillow@9.4.0

2. Which CVE is linked to this vulnerability?
    CVE-2023-44271

3. What remediation steps do you suggest?
    the affected range is <10.0.0, so in requirements.txt we should mention the version of package equal to or above 10.0.0 eg: Pillow==10.0.0


### Vulnerability 2:
1. Which vulnerability are you addressing?
    pkg:pypi/sqlparse@0.3.1

2. Which CVE is linked to this vulnerability?
    CVE-2024-4340

3. What remediation steps do you suggest? 
    the affected range is <0.5.0, so in requirements.txt we should mention the version of package equal to or above 0.5.0 eg: sqlparse==0.5.0