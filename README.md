# OCVS-Cloud
OCVS-Cloud Scenarios Case Studies Infrastruture Designs


A high-profile customer wants to migrate to OCVS. The customer has multiple lines of business such as Finance, Engineering, and Sales utilizing their on-premise VMware environment. Finance needs the ability to work with Engineering and Sales. Engineering has highly confidential information and doesn’t want their workloads to be seen by sales (because they try to sell products before its released!). This customer has expressed interest in migrating the entire environment into Oracle Cloud VMware Solution. Design a OCVS solution for their environment which includes 300 databases (600 cores, 600 TB storage). There are other workloads such as Web Servers and Application servers as well. The customer has made it clear that their databases should never experience any downtime, and once in the cloud, they can’t tolerate an Oracle regional outage

Document your plan to migrate this environment into Oracle Cloud. The plan should include diagrams that cover:
- How will the customer migrate from on-prem to the cloud?
- How do you meet the access requirements by the different lines of business?
- Document the NSX Edge firewall / DFW firewall topology.
- Document the NSX T0 and T1 topology ...
- What storage optimizations can you make to ensure the availability of the critical databases?
- How do you solve for HA/DR for this use case?

- In the Attached PPT it has a High level Design and details of migration including above questions answered in other slides.
- 
