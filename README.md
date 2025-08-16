# Amazon Inspector Code Security feature

Amazon Inspector Code Security – now with native **GitHub** and **GitLab** integration.  
Lets you scan for vulnerabilities **before your code reaches production**.

---

## Resources

1. **Vulnerable Code**  
   - `vulnerablecode.py` (script kiddie stuff)

2. **GitHub**  
   - Commit the vulnerable code into a repo

3. **Amazon Inspector**  
   - Automatically scan repo using Amazon Inspector  
   - Inspector highlights issues such as **OS Command Injection**, **Cloudformation-public-read-bucket-ACL**, **SQL Injection**, and **Unsafe Deserialization**

4. **Application**  
   - Findings can be reviewed and fixed before pushing the code into production

---

## Steps

1. **Login** to the AWS Management Console.
2. **Search for Amazon Inspector** and enable service.  
3. **Connect GitHub repository** that contains `vulnerablecode.py`or your vulnerable code.  
4. **Enable Code Scanning** under Inspector → Code Scans.  
5. **Inspector** analyzes the code repo's when Github has been authorized OR you can initiate an **On-Demand scan**.
6. **Review Findings** – Inspector will list vulnerabilities, their severity, and remediation advice.  
7. **Fix Issues and Commit** changes back to GitHub.  
8. **Repeat Scans** until the repository is free of critical vulnerabilities.  
9. **Clean Up** – disable resources if not needed to avoid extra cost.

---
