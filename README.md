# Awesome VMware Carbon Black 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Carbon Black materials and resources.

# Contents
- [Official Resources](#official-resources)
- [Carbon Black Cloud](#carbon-black-cloud)
- [Cloud Workload Protection](#cloud-workload-protection)
- [Threat Hunting](#threat-hunting)
- [API](#api)
- [Development](#development)
- [Integrations](#integrations)
- [VMworld 2020 Sessions](#vmworld-2020-sessions)


## Official Resources 
- [User Community](https://community.carbonblack.com/) - Official user community for discussions, threat analysis reports and more.
- [Carbon Black Tech Zone](https://carbonblack.vmware.com/) - Official technical resources.
- [Documentation CBC](https://docs-staging.vmware.com/en/VMware-Carbon-Black-Cloud/services/carbon-black-cloud-user-guide/GUID-E55A92B9-B0C8-481E-97A0-61B997F4EAD3.html) - Official Carbon Black Cloud documentation.
- [TAU Tools](https://github.com/carbonblack/tau-tools) - Tools developed by the Threat Analysis Unit.
- [Ask The Howlers](https://www.carbonblack.com/resources/ask-the-howlers/) - Webinar series on latest threats and security challenges.
- [Carbon Black Blog](https://www.carbonblack.com/blog/) - Official Carbon Black blog posts.
- [Youtube](https://www.youtube.com/c/Carbonblack-Incorporated/) - Official Youtube channel.
- [Training](https://www.carbonblack.com/training/) - Official Training.

## Carbon Black Cloud
- [Network Setup](https://community.carbonblack.com/t5/Knowledge-Base/Carbon-Black-Cloud-What-Ports-must-be-opened-on-the-Firewall-and/ta-p/36295) - Ports to be opened on the Firewall and Proxy Servers.
- [Kirk's Defense Kung Fu Blog](https://community.carbonblack.com/t5/Endpoint-Standard-Documents/Kirk-s-Defense-Kung-Fu-Blog/ta-p/67558) - One of the best sources for good pactises and tips.
- [A+R Best Practices Guide](https://community.carbonblack.com/t5/Audit-and-Remediation-Documents/Audit-and-Remediation-Best-Practices-Guide/ta-p/102685) - Audit & Remediation Guide / Tutorial
- [Good, Better, Best Policies](https://community.carbonblack.com/t5/Endpoint-Standard-Discussions/Endpoint-Standard-Achieving-Good-Better-and-Best-Policies/m-p/40957/highlight/true#M3832) - Tips for developing policies and improving them.
- [Live Response: Use Cases](https://community.carbonblack.com/t5/Best-Practices/Live-Response-Use-Cases-and-Examples/gpm-p/80004) - Collection of KBs and discussions showcasing different uses of Live Response
- [How VMware IT Deployed and Adopted Carbon Black Cloud](https://www.youtube.com/watch?v=VDrxddC3uHg&t=990s) - Valuable insight how VMware enrolled Carbon Black internally. 

## Cloud Workload Protection
- [Documentation CWP](https://docs-staging.vmware.com/en/VMware-Carbon-Black-Cloud-Workload/index.html) - Official CWP documentation.
- [Modern Clouds](https://modernclouds.blog/2021/01/19/unboxing-the-new-carbon-black-container-security-solution/) - Unboxing the new VMware Carbon Black container security solution.
- [Container Security: VMC on AWS](https://www.securefever.com/blog/vmware-carbon-black-cloud-container-security-with-vmc-on-aws) - VMware Carbon Black Cloud Container Security with VMC on AWS

## Threat Hunting
- [Recon Hunt Queries](https://rhq.reconinfosec.com/) - Audit & Remediation queries for incident response & threat hunting.
- [osquery + ATT&CK](https://github.com/teoseller/osquery-attck) - Audit & Remediation queries mapped to MITRE ATT&CK Framework.
- [osquery across compliance, monitoring, risk, and threat hunting](https://www.youtube.com/watch?v=zQFXLm-SweY&t=5s) - Talk on osquery by Hugh Neale.
- [WinRM Hunting](https://community.carbonblack.com/t5/Threat-Research-Docs/WinRM-Threat-Hunting-Part-1/ta-p/88100) - Hunting WinRM misuse.
- [svchost Hunting](https://community.carbonblack.com/t5/Threat-Research-Docs/Basic-Primer-on-SVCHOST-Threat-Hunting-Queries/ta-p/90099) - Hunt for malicious svchost.

## API
- [CBinterface](https://github.com/ace-ecosystem/cbinterface2) - Command line tool and library for interfacing with one or more Carbon Black environments.
- [Qt API](https://github.com/slist/cbapi-qt-demo) - Useful tool for comparing policies and more.
- [Automated Response Action](https://community.carbonblack.com/t5/Developer-Relations-Docs/PSC-LiveResponse-Via-Postman-Example-Automated-Response-Actions/ta-p/89567) - Automation of response actions with Live Response and Postman. 
- [REST API Tutorial Using Postman](https://developer.carbonblack.com/2018/05/cb-defense-rest-api-tutorial-using-postman/) - Tutorial on how to automate API requests with Postman.

## Development
- [Github](https://github.com/carbonblack) - Official Carbon Black Github repository.
- [API Documentation](https://developer.carbonblack.com/) - Official API documentation for all Carbon Black products.
- [Python SDK](https://github.com/carbonblack/carbon-black-cloud-sdk-python) - Official Carbon Black Software Development Kit for Python 3.6 and above.
- [Binary Toolkit](https://github.com/carbonblack/cbc-binary-toolkit)

## Integrations
- **[Threat Intelligence Feeds]**
  - [EEDR TAXII Connector](https://www.youtube.com/watch?v=063bzg4jc0U) - How to Ingest 3rd-Party Feeds into Enterprise EDR
- **[Splunk]**
  - [Splunk App](https://splunkbase.splunk.com/app/5332/) - Carbon Black App for Splunk. 
  - [Columbus Splunk UG Aug 18 2020](https://www.youtube.com/watch?v=jnvmb5pqnxI) - Review of Carbon Black Splunk Add-on and Threat Hunter Dashboard
  - [Carbon Black App for Splunk](https://www.securefever.com/blog/carbon-black-app-for-splunk) - Blog on setting up the Carbon Black App for Splunk.
- **[Workspace ONE]**
  - [Workspace ONE Integration Demo](https://www.youtube.com/watch?v=bAZIxhkuJhU&t=189s) - Carbon Black / Workspace One integration feature walkthrough.
  - [Automating Device Quarantine Feature Walkthrough](https://www.youtube.com/watch?v=bAZIxhkuJhU) - Automation Demo
  - [Custom Connector Sample Collection](https://github.com/vmware-samples/euc-samples/tree/master/Intelligence-Samples/Custom%20Connectors/CarbonBlack) - Automation workflows for Workspace ONE Intelligence
- **[Other Integrations]**
  - [Siemplify](https://www.siemplify.co/partners/carbon-black/) - SOAR integration with Siemplify.
  - [Zscaler](https://www.youtube.com/watch?v=dfF-JPmlaXA&t=1s) - [Demo] VMWare Carbon Black and Zscaler in Action
  - [MISP](https://github.com/eCrimeLabs/MISP2CbR) - MISP Integration for EDR (On-Premise).

## VMworld 2020 Security Sessions
- [The "Future Ready" Security Operations Center](https://www.vmworld.com/en/video-library/video-landing.html?sessionid=1596071231908001rlwZ)
- [Comprehensive Workload Security: vSphere, NSX, and Carbon Black Cloud](https://www.vmworld.com/en/video-library/video-landing.html?sessionid=1591280408543001VI9S)
- [Flexibly SOAR Toward API Functionality With Carbon Black](https://www.vmworld.com/en/video-library/video-landing.html?sessionid=1585033737089001NaRI)
- [VMware Security: VMware Carbon Black Cloud and Workspace ONE Intelligence](https://www.vmworld.com/en/video-library/video-landing.html?sessionid=1584621522711001DIlS)
- [XDR EDR: How VMware's Integrations Re-Shape Protecting Your Assets](https://www.vmworld.com/en/video-library/video-landing.html?sessionid=1596214249540001Eav9)
- [Become a Threat Hunter](https://www.vmworld.com/en/video-library/video-landing.html?sessionid=1591217036405001PNXo)
