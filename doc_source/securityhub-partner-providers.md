# Available third\-party partner product integrations<a name="securityhub-partner-providers"></a>

AWS Security Hub is integrated with the following third\-party products\. For each provider, the list indicates how the integration interacts with findings\. An integration can perform the following actions:
+ Send findings that it generates to Security Hub\.
+ Receive findings from Security Hub\.
+ Update findings in Security Hub\. Integrations that receive findings from Security Hub might also update those findings\.

Integrations that send findings to Security Hub have an ARN\.

**Note**  
Some integrations are not available in all Regions\.  
If an integration is not supported, it is not listed on the console **Integrations** page  
See also [Integrations that are supported in China \(Beijing\) and China \(Ningxia\)](securityhub-regions.md#securityhub-regions-integration-support-china) and [Integrations that are supported in AWS GovCloud \(US\-East\) and AWS GovCloud \(US\-West\)](securityhub-regions.md#securityhub-regions-integration-support-govcloud)\.

If you have a security solution and are interested in becoming a Security Hub partner, send an email to securityhub\-partners@amazon\.com\. In the message, provide your company name, product name, AWS Partner Network \(APN\) tier level, and contact information\.

To become a Security Hub partner, you must meet one of the following criteria:
+ You are an AWS Select Tier Partner or above\.
+ You have joined the [AWS ISV Partner Path](http://aws.amazon.com/partners/isv/), and the product that you use for Security Hub integration has completed an [AWS Foundational Technical Review \(FTR\)](http://aws.amazon.com/partners/foundational-technical-review/)\. The product is then granted a "Reviewed by AWS" badge\.

To get started, read through the [https://docs.aws.amazon.com/securityhub/latest/partnerguide/integration-overview.html](https://docs.aws.amazon.com/securityhub/latest/partnerguide/integration-overview.html)\. After you review the onboarding information, you can begin to work on your product manifest\.

## 3CORESec – 3CORESec NTA \(Sends findings\)<a name="integration-3coresec-nta"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/3coresec/3coresec`

3CORESec provides managed detection services for both on\-premises and AWS systems\. Their integration with Security Hub allows visibility into threats such as malware, privilege escalation, lateral movement, and improper network segmentation\.

[Product link](https://3coresec.com/aws)

[Partner documentation](https://docs.google.com/document/d/1TPUuuyoAVrMKRVnGKouRy384ZJ1-3xZTnruHkIHJqWQ/edit?usp=sharing)

## Alert Logic – SIEMless Threat Management \(Sends findings\)<a name="integration-alert-logic-siemless"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:733251395267:product/alertlogic/althreatmanagement`

Get the right level of coverage: vulnerability and asset visibility, threat detection and incident management, AWS WAF, and assigned SOC analyst options\.

[Product link](https://www.alertlogic.com/solutions/platform/aws-security/)

[Partner documentation](https://docs.alertlogic.com/configure/aws-security-hub.htm)

## Aqua Security – Aqua Cloud Native Security Platform \(Sends findings\)<a name="integration-aqua-security-cloud-native-security-platform"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/aquasecurity/aquasecurity`

Aqua Cloud Native Security Platform \(CSP\) provides full lifecycle security for container\-based and serverless applications, from your CI/CD pipeline to runtime production environments\.

[Product link](https://blog.aquasec.com/aqua-aws-security-hub)

[Partner documentation](https://github.com/aquasecurity/aws-security-hub-plugin)

## Aqua Security – Kube\-bench \(Sends findings\)<a name="integration-aqua-security-kubebench"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/aqua-security/kube-bench`

Kube\-bench is an open\-source tool that runs the Center for Internet Security \(CIS\) Kubernetes Benchmark against your environment\.

[Product link](https://github.com/aquasecurity/kube-bench/blob/master/README.md)

[Partner documentation](https://github.com/aquasecurity/kube-bench/blob/master/README.md)

## Armor – Armor Anywhere \(Sends findings\)<a name="integration-armor-anywhere"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:679703615338:product/armordefense/armoranywhere`

Armor Anywhere delivers managed security and compliance for AWS\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=797425f4-6823-4cf6-82b5-634f9a9ec347)

[Partner documentation](https://amp.armor.com/account/cloud-connections)

## Atlassian \- Jira Service Management \(Receives and updates findings\)<a name="integration-atlassian-jira-service-management"></a>

**Integration type:** Receive and update

The AWS Service Management Connector for Jira sends findings from Security Hub to Jira\. Jira issues are created based on the findings\. When the Jira issues are updated, the corresponding findings are updated in Security Hub\.

The integration only supports Jira Server and Jira Data Center\.

For an overview of the integration and how it works, watch the video [AWS Security Hub – Bidirectional integration with Atlassian Jira Service Management](https://www.youtube.com/watch?v=uEKwu0M8S3M)\.

[Product link](https://www.atlassian.com/software/jira/service-management)

[Partner documentation](https://docs.aws.amazon.com/servicecatalog/latest/adminguide/integrations-jiraservicedesk.html)

## Atlassian – Opsgenie \(Receives findings\)<a name="integration-atlassian-opsgenie"></a>

**Integration type:** Receive

Opsgenie is a modern incident management solution for operating always\-on services, empowering development and operations teams to plan for service disruptions and stay in control during incidents\.

Integrating with Security Hub ensures that mission critical security\-related incidents are routed to the appropriate teams for immediate resolution\.

[Product link](https://www.atlassian.com/software/opsgenie)

[Partner documentation](https://docs.opsgenie.com/docs/amazon-security-hub-integration-bidirectional)

## AttackIQ – AttackIQ \(Sends findings\)<a name="integration-attackiq"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/attackiq/attackiq-platform`

AttackIQ Platform emulates real adversarial behavior aligned with the MITRE ATT&CK Framework to help validate and improve your overall security posture\.

[Product link](https://go.attackiq.com/BD-AWS-Security-Hub_LP.html)

[Partner documentation](https://github.com/AttackIQ/attackiq.github.io)

## Barracuda Networks – Cloud Security Guardian \(Sends findings\)<a name="integration-barracuda-cloud-security-guardian"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:151784055945:product/barracuda/cloudsecurityguardian`

Barracuda Cloud Security Sentry helps organizations stay secure while building applications in, and moving workloads to, the public cloud\.

[AWS Marketplace link](http://aws.amazon.com/marketplace/pp/B07KF2X7QJ)

[Product link](https://www.barracuda.com/aws/solutions/csg)

## BigID – BigID Enterprise \(Sends findings\)<a name="integration-bigid-enterprise"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/bigid/bigid-enterprise`

The BigID Enterprise Privacy Management Platform helps companies manage and protect sensitive data \(PII\) across all their systems\.

[Product link](https://github.com/bigexchange/aws-security-hub)

[Partner documentation](https://github.com/bigexchange/aws-security-hub)

## Blue Hexagon – Blue Hexagon forAWS \(Sends findings\)<a name="integration-blue-hexagon-for-aws"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/blue-hexagon/blue-hexagon-for-aws`

Blue Hexagon is a real time threat detection platform\. It uses deep learning principles to detect known and unknown threats, including malware and network anomalies\.

[Product link](https://bluehexagon.ai/solutions/secure-my-aws-workloads/)

[Partner documentation](https://bluehexagonai.atlassian.net/wiki/spaces/BHDOC/pages/395935769/Deploying+Blue+Hexagon+with+AWS+Traffic+Mirroring#DeployingBlueHexagonwithAWSTrafficMirroringDeployment-Integrations)

## Capitis Solutions – C2VS \(Sends findings\)<a name="integration-capitis-c2vs"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/capitis/c2vs`

C2VS is a customizable compliance solution designed to automatically identify your application\-specific misconfigurations and their root cause\.

[Product link](https://www.capitissolutions.com/security-hub-integration/)

[Partner documentation](https://www.capitissolutions.com/security-hub-configuration/)

## Caveonix – Caveonix Cloud \(Sends and receives findings\)<a name="integration-caveonix-cloud"></a>

**Integration type:** Send and receive

**Product ARN:** `arn:aws:securityhub:<REGION>::product/caveonix/caveonix-cloud`

Caveonix Cloud is a SaaS risk mitigation platform that delivers automated compliance and hybrid\-cloud security posture management for comprehensive workload protection\.

[Product link](http://aws.amazon.com/marketplace/pp/B087Y37BTD)

[Partner documentation](https://www.caveonix.com/support/aws-security-hub)

## Check Point – CloudGuard IaaS \(Sends findings\)<a name="integration-checkpoint-cloudguard-iaas"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:758245563457:product/checkpoint/cloudguard-iaas`

Check Point CloudGuard easily extends comprehensive threat prevention security to AWS while protecting assets in the cloud\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=a979fc8a-dd48-42c8-84cc-63d5d50e3a2f)

[Partner documentation](https://supportcenter.checkpoint.com/supportcenter/portal?eventSubmit_doGoviewsolutiondetails=&solutionid=sk140412)

## Check Point – CloudGuard Posture Management \(Sends findings\)<a name="integration-checkpoint-cloudguard-posture-management"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:634729597623:product/checkpoint/dome9-arc`

A SaaS platform that delivers verifiable cloud network security, advanced IAM protection, and comprehensive compliance and governance\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=a979fc8a-dd48-42c8-84cc-63d5d50e3a2f)

[Partner documentation](https://supportcenter.checkpoint.com/supportcenter/portal?eventSubmit_doGoviewsolutiondetails=&solutionid=sk144592&partition=General&product=CloudGuard)

## Cloud Custodian – Cloud Custodian \(Sends and receives findings\)<a name="integration-cloud-custodian"></a>

**Integration type:** Send and receive

**Product ARN:** `arn:aws:securityhub:<REGION>::product/cloud-custodian/cloud-custodian`

Cloud Custodian enables users to be well managed in the cloud\. The simple YAML DSL allows easily defined rules to enable a well\-managed cloud infrastructure that's both secure and cost optimized\.

[Product link](https://cloudcustodian.io/docs/aws/topics/securityhub.html)

[Partner documentation](https://cloudcustodian.io/docs/aws/topics/securityhub.html)

## Cloud Storage Security – Antivirus for Amazon S3 \(Sends findings\)<a name="integration-cloud-storage-security-antivirus-for-s3"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/cloud-storage-security/antivirus-for-amazon-s3`

Cloud Storage Security provides cloud native anti\-malware and antivirus scanning for Amazon S3 objects\.

Antivirus for Amazon S3 offers real time and scheduled scans of objects and files in Amazon S3 for malware and threats\. It provides visibility and remediation for problem and infected files\.

[Product link](https://cloudstoragesec.com/)

[Partner documentation](https://help.cloudstoragesec.com/console-overview/console-settings/#send-scan-result-findings-to-aws-security-hub)

## cloudtamer\.io – cloudtamer\.io \(Sends and receives findings\)<a name="integration-cloudtamerio"></a>

**Integration type:** Send and receive

**Product ARN:** `arn:aws:securityhub:<REGION>::product/cloudtamerio/cloudtamerio`

cloudtamer\.io is a complete cloud governance solution for AWS\. cloudtamer\.io gives stakeholders visibility into cloud operations and helps cloud users manage accounts, control budget and cost, and ensure continuous compliance\.

[Product link](https://www.cloudtamer.io/partners/aws/)

[Partner documentation](https://cloudtamer.zendesk.com/hc/en-us/articles/360046647551)

## CrowdStrike – CrowdStrike Falcon \(Sends findings\)<a name="integration-crowdstrike-falcon"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:517716713836:product/crowdstrike/crowdstrike-falcon`

The CrowdStrike Falcon single, lightweight sensor unifies next\-generation antivirus, endpoint detection and response, and 24/7 managed hunting through the cloud\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=f4fb055a-5333-4b6e-8d8b-a4143ad7f6c7)

[Partner documentation](https://www.crowdstrike.com/blog/tech-center/crowdstrike-aws-security-hub/)

## CyberArk – Privileged Threat Analytics \(Sends findings\)<a name="integration-cyberark-privileged-threat-analytics"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:749430749651:product/cyberark/cyberark-pta`

Privileged Threat Analytics collect, detect, alert, and respond to high\-risk activity and behavior of privileged accounts to contain in\-progress attacks\.

[Product link](https://www.cyberark.com/solutions/digital-transformation/cloud-virtualization-security/)

[Partner documentation](https://cyberark-customers.force.com/mplace/s/#a352J000000dZATQA2-a392J000001Z3eaQAC)

## Data Theorem \(Sends findings\)<a name="integration-data-theorem"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/data-theorem/api-cloud-web-secure`

Data Theorem continuously scans web applications, APIs, and cloud resources in search of security flaws and data privacy gaps to prevent AppSec data breaches\.

[Product link](https://www.datatheorem.com/partners/aws/)

[Partner documentation](https://datatheorem.atlassian.net/wiki/spaces/PKB/pages/1730347009/AWS+Security+Hub+Integration)

## DisruptOps, Inc\. – DisruptOPS \(Sends and receives findings\)<a name="integration-disruptops"></a>

**Integration type:** Send and receive

**Product ARN:** `arn:aws:securityhub:<REGION>::product/disruptops-inc/disruptops`

The DisruptOps Security Operations Platform helps organizations maintain best security practices in your cloud through the use of automated guardrails\.

[Product link](https://disruptops.com/ad/securityhub-isa/)

[Partner documentation](https://disruptops.com/securityhub/)

## FireEye – FireEye Helix \(Receives findings\)<a name="integration-fireeye-helix"></a>

**Integration type:** Receive

FireEye Helix is a cloud\-hosted security operations platform that allows organizations to take control of any incident from alert to fix\.

[Product link](https://www.fireeye.com/solutions/helix.html)

[Partner documentation](https://docs.fireeye.com/docs/index.html#helix)

## Forcepoint – Forcepoint CASB \(Sends findings\)<a name="integration-forcepoint-casb"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:365761988620:product/forcepoint/forcepoint-casb`

Forcepoint CASB allows you to discover cloud application use, analyze risk, and enforce appropriate controls for SaaS and custom applications\.

[Product link](https://www.forcepoint.com/platform/technology-partners/securing-your-amazon-web-services-aws-workloads)

[Partner documentation](https://frcpnt.com/casb-securityhub)

## Forcepoint – Forcepoint Cloud Security Gateway \(Sends findings\)<a name="integration-forcepoint-cloud-security-gateway"></a>

**Integration type:** Send

Product ARN: `arn:aws:securityhub:<REGION>::product/forcepoint/forcepoint-cloud-security-gateway`

Forcepoint Cloud Security Gateway is a converged cloud security service that provides visibility, control, and threat protection for users and data, wherever they are\.

[Product link](https://www.forcepoint.com/product/cloud-security-gateway)

[Partner documentation](https://forcepoint.github.io/docs/csg_and_aws_security_hub/#forcepoint-cloud-security-gateway-and-aws-security-hub)

## Forcepoint – Forcepoint DLP \(Sends findings\)<a name="integration-forcepoint-dlp"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:365761988620:product/forcepoint/forcepoint-dlp`

Forcepoint DLP addresses human\-centric risk with visibility and control everywhere your people work and everywhere your data resides\.

[Product link](https://www.forcepoint.com/platform/technology-partners/securing-your-amazon-web-services-aws-workloads)

[Partner documentation](https://frcpnt.com/dlp-securityhub)

## Forcepoint – Forcepoint NGFW \(Sends findings\)<a name="integration-forcepoint-ngfw"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:365761988620:product/forcepoint/forcepoint-ngfw`

Forcepoint NGFW lets you connect your AWS environment into your enterprise network with the scalability, protection, and insights needed to manage your network and respond to threats\.

[Product link](https://www.forcepoint.com/platform/technology-partners/securing-your-amazon-web-services-aws-workloads)

[Partner documentation](https://frcpnt.com/ngfw-securityhub)

## Fortinet – FortiCNP \(Receives findings\)<a name="integration-fortinet-forticnp"></a>

**Integration type:** Receive

**Product ARN:** `arn:aws:securityhub:<REGION>::product/fortinet-inc/forticnp-cloud-native-protection`

FortiCNP is a Cloud Native Protection product that aggregates security findings into actionable insights and prioritizes security insights based on risk score to reduce alert fatigue and accelerate remediation\.

[AWS Marketplace link](https://aws.amazon.com/marketplace/pp/prodview-vl24vc3mcb5ak)

[Partner documentation](https://docs.fortinet.com/document/forticnp/22.3.a/online-help/467775/aws-security-hub-configuration)

## Fugue – Fugue \(Sends findings\)<a name="integration-fugue"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/fugue/fugue`

Fugue is an agent\-less, scalable cloud\-native platform that automates the continuous validation of infrastructure\-as\-code and cloud runtime environments using the same policies\.

[Product link](https://www.fugue.co/aws-security-hub-integration)

[Partner documentation](https://docs.fugue.co/integrations-aws-security-hub.html)

## Guardicore – Centra 4\.0 \(Sends findings\)<a name="integration-guardicore-centra"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:324264561773:product/guardicore/guardicore`

Guardicore Centra provides flow visualization, micro\-segmentation, and breach detection for workloads in modern data centers and clouds\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=21127457-7622-49be-81a6-4cb5dd77a088)

[Partner documentation](https://customers.guardicore.com/login)

## Guardicore – Infection Monkey \(Sends findings\)<a name="integration-guardicore-infection-monkey"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:324264561773:product/guardicore/aws-infection-monkey`

Infection Monkey is an attack simulation tool designed to test networks against attackers\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=21127457-7622-49be-81a6-4cb5dd77a088)

[Partner documentation](https://www.guardicore.com/infectionmonkey/docs/usage/integrations/aws-security-hub/)

## HackerOne – Vulnerability Intelligence \(Sends findings\)<a name="integration-hackerone-vulnerability-intelligence"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/hackerone/vulnerability-intelligence`

The HackerOne platform partners with the global hacker community to uncover the most relevant security issues\. Vulnerability Intelligence enables your organization to go beyond automated scanning\. It shares vulnerabilities that HackerOne ethical hackers have validated and provided steps to reproduce\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=10857e7c-011b-476d-b938-b587deba31cf)

[Partner documentation](https://docs.hackerone.com/programs/aws-security-hub-integration.html)

## Helecloud – Managed Security \(Receives findings\)<a name="integration-helecloud-managed-security"></a>

**Integration type:** Receive

HeleCloud is a Managed Services Provider, taking care of your AWS infrastructure so that you can focus on your core business\.

[Product link](https://helecloud.com/managed-security-and-compliance-services/)

## IBM – QRadar \(Receives findings\)<a name="integration-ibm-qradar"></a>

**Integration type:** Receive

**Product ARN:** `arn:aws:securityhub:<REGION>:949680696695:product/ibm/qradar-siem`

IBM QRadar SIEM provides security teams with the ability to quickly and accurately detect, prioritize, investigate, and respond to threats\.

[Product link](https://www.ibm.com/security/security-intelligence/qradar/securing-the-cloud)

[Partner documentation](https://www.ibm.com/docs/en/qradar-common?topic=configuration-integrating-aws-security-hub)

## JFrog – Xray \(Sends findings\)<a name="integration-jfrog-xray"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/jfrog/jfrog-xray`

JFrog Xray is a universal application security Software Composition Analysis \(SCA\) tool that continuously scans binaries for license compliance and security vulnerabilities so that you can run a secure software supply chain\.

[AWS Marketplace link](http://aws.amazon.com/marketplace/seller-profile?id=68002c4f-c9d1-4fa7-b827-fd7204523fb7)

[Partner documentation](https://www.jfrog.com/confluence/display/JFROG/Xray+Integration+with+AWS+Security+Hub)

## Juniper Networks – vSRX Next Generation Firewall \(Sends findings\)<a name="integration-junipernetworks-vsrxnextgenerationfirewall"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/juniper-networks/vsrx-next-generation-firewall`

Juniper Networks' vSRX Virtual Next Generation Firewall delivers a complete cloud\-based virtual firewall with advanced security, secure SD\-WAN, robust networking, and built\-in automation\.

[AWS Marketplace link](http://aws.amazon.com/marketplace/pp/prodview-z7jcugjx442hw)

[Partner documentation](https://www.juniper.net/documentation/us/en/software/vsrx/vsrx-consolidated-deployment-guide/vsrx-aws/topics/topic-map/security-aws-cloudwatch-security-hub-and-logs.html#id-enable-and-configure-security-hub-on-vsrx)

[Product link](https://www.juniper.net/documentation/us/en/software/vsrx/vsrx-consolidated-deployment-guide/vsrx-aws/topics/topic-map/security-aws-cloudwatch-security-hub-and-logs.html)

## k9 Security – Access Analyzer \(Sends findings\)<a name="integration-k9-security-access-analyzer"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/k9-security/access-analyzer`

k9 Security notifies you when important access changes occur in your AWS Identity and Access Management account\. With k9 Security, you can understand the access that each IAM user and role has to critical AWS services and your data\.

k9 Security is built for continuous delivery, allowing you to operationalize IAM with actionable access audits and simple policy automation for AWS CDK and Terraform\.

[Product link](https://www.k9security.io/lp/operationalize-aws-iam-security-hub)

[Partner documentation](https://www.k9security.io/docs/how-to-configure-k9-access/)

## Lacework \(Sends findings\)<a name="integration-lacework"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/lacework/lacework`

Lacework is the data\-driven security platform for the cloud\. The Lacework Cloud Security Platform automates cloud security at scale so you can innovate with speed and safety\.

[Product link](https://www.lacework.com/platform/aws/)

[Partner documentation](https://lacework-alliances.netlify.app/aws-security-hub-integration/)

## Logz\.io Cloud SIEM \(Receives findings\)<a name="integration-logzio-cloud-siem"></a>

**Integration type:** Receive

Logz\.io is a provider of Cloud SIEM that provides advanced correlation of log and event data to help security teams to detect, analyze, and respond to security threats in real time\.

[Product link](https://logz.io/solutions/cloud-monitoring-aws/)

[Partner documentation](https://docs.logz.io/shipping/security-sources/aws-security-hub.html)

## McAfee – MVISION Cloud Native Application Protection Platform \(CNAPP\) \(Sends findings\)<a name="integration-mcafee-mvision-cnapp"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:297986523463:product/mcafee-skyhigh/mcafee-mvision-cloud-aws`

McAfee MVISION Cloud Native Application Protection Platform \(CNAPP\) offers Cloud Security Posture Management \(CSPM\) and Cloud Workload Protection Platform \(CWPP\) for your AWS environment\.

[Product link](https://aws.amazon.com/marketplace/pp/prodview-ol6txkzkdyacc)

[Partner documentation](https://success.myshn.net/Cloud_Native_Application_Protection_Platform_(IaaS)/Amazon_Web_Services_(AWS)/Integrate_MVISION_Cloud_with_AWS_Security_Hub)

## MicroFocus – MicroFocus Arcsight \(Receives findings\)<a name="integration-microfocus-arcsight"></a>

**Integration type:** Receive

ArcSight accelerates effective threat detection and response in real time, integrating event correlation and supervised and unsupervised analytics with response automation and orchestration\.

[Product link](http://aws.amazon.com/marketplace/pp/B07RM918H7)

[Partner documentation](https://community.microfocus.com/cyberres/productdocs/w/connector-documentation/2768/smartconnector-for-amazon-web-services-security-hub)

## NETSCOUT – NETSCOUT Cyber Investigator \(Sends findings\)<a name="integration-netscout-cyber-investigator"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:us-east-1::product/netscout/netscout-cyber-investigator`

NETSCOUT Cyber Investigator is an enterprise\-wide network threat, risk investigation, and forensic analysis platform that helps to reduce the impact of cyber threats on businesses\.

[Product link](http://aws.amazon.com/marketplace/pp/prodview-reujxcu2cv3f4?qid=1608874215786&sr=0-1&ref_=srh_res_product_title)

[Partner documentation](https://www.netscout.com/solutions/cyber-investigator-aws)

## PagerDuty – PagerDuty \(Receives findings\)<a name="integration-pagerduty"></a>

**Integration type:** Receive

The PagerDuty digital operations management platform empowers teams to proactively mitigate customer\-impacting issues by automatically turning any signal into the right insight and action\.

AWS users can use the PagerDuty set of AWS integrations to scale their AWS and hybrid environments with confidence\.

When coupled with Security Hub aggregated and organized security alerts, PagerDuty allows teams to automate their threat response process and quickly set up custom actions to prevent potential issues\.

PagerDuty users who are undertaking a cloud migration project can move quickly, while decreasing the impact of issues that occur throughout the migration lifecycle\.

[Product link](http://aws.amazon.com/marketplace/pp/prodview-5sf6wkximaixc?ref_=srh_res_product_title)

[Partner documentation](https://support.pagerduty.com/docs/aws-security-hub-integration-guide-pagerduty)

## Palo Alto Networks – Cortex XSOAR \(Receives findings\)<a name="integration-palo-alto-cortex-xsoar"></a>

**Integration type:** Receive

Cortex XSOAR is a Security Orchestration, Automation, and Response \(SOAR\) platform that integrates with your entire security product stack to accelerate incident response and security operations\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=0ed48363-5064-4d47-b41b-a53f7c937314)

[Partner documentation](https://xsoar.pan.dev/docs/reference/integrations/aws---security-hub)

## Palo Alto Networks – Prisma Cloud Compute \(Sends findings\)<a name="integration-palo-alto-prisma-cloud-compute"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:496947949261:product/twistlock/twistlock-enterprise`

Prisma Cloud Compute is a cloud native cybersecurity platform that protects VMs, containers, and serverless platforms\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=0ed48363-5064-4d47-b41b-a53f7c937314)

[Partner documentation](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute/alerts/aws_security_hub.html)

## Palo Alto Networks – Prisma Cloud Enterprise \(Sends findings\)<a name="integration-palo-alto-prisma-cloud-enterprise"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:188619942792:product/paloaltonetworks/redlock`

Protects your AWS deployment with cloud security analytics, advanced threat detection, and compliance monitoring\.

[Product link](http://aws.amazon.com/marketplace/seller-profile?id=0ed48363-5064-4d47-b41b-a53f7c937314)

[Partner documentation](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin/configure-external-integrations-on-prisma-cloud/integrate-prisma-cloud-with-aws-security-hub)

## Palo Alto Networks – VM\-Series \(Receives findings\)<a name="integration-palo-alto-vmseries"></a>

**Integration type:** Receive

Palo Alto VM\-Series integration with Security Hub collects threat intelligence and sends it to the VM\-Series next\-generation firewall as an automatic security policy update that blocks malicious IP address activity\.

[Product link](https://github.com/PaloAltoNetworks/pan_aws_security_hub)

[Partner documentation](https://github.com/PaloAltoNetworks/pan_aws_security_hub)

## Prowler \(Sends findings\)<a name="integration-prowler"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/prowler/prowler`

Prowler is an open source security tool to perform AWS checks related to security best practices, hardening, and continuous monitoring\.

[Product link](https://github.com/prowler-cloud/prowler)

[Partner documentation](https://github.com/prowler-cloud/prowler#security-hub-integration)

## Qualys – Vulnerability Management \(Sends findings\)<a name="integration-qualys-vulnerability-management"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:805950163170:product/qualys/qualys-vm`

Qualys Vulnerability Management \(VM\) continuously scans and identifies vulnerabilities, protecting your assets\.

[Product link](https://www.qualys.com/public-cloud/#aws)

[Partner documentation](https://qualys-secure.force.com/discussions/s/article/000005831)

## Rackspace Technology – Cloud Native Security \(Receives findings\)<a name="integration-rackspace-cloud-native-security"></a>

**Integration type:** Receive

Rackspace Technology provides managed security services on top of native AWS security products for 24x7x365 monitoring by Rackspace SOC, advanced analysis, and threat remediation\.

[Product link](https://www.rackspace.com/managed-aws/capabilities/security)

## Rapid7 – InsightConnect \(Receives findings\)<a name="integration-rapid7-insightconnect"></a>

**Integration type:** Receive

Rapid7 InsightConnect is a security orchestration and automation solution that enables your team to optimize SOC operations with little to no code\.

[Product link](https://www.rapid7.com/partners/technology-partners/amazon-web-services/)

[Partner documentation](https://docs.rapid7.com/insightconnect/aws-security-hub/)

## Rapid7 – InsightVM \(Sends findings\)<a name="integration-rapid7-insightvm"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:336818582268:product/rapid7/insightvm`

Rapid7 InsightVM provides vulnerability management for modern environments, allowing you to efficiently find, prioritize, and remediate vulnerabilities\.

[Product link](https://www.rapid7.com/partners/technology-partners/amazon-web-services/)

[Partner documentation](https://docs.rapid7.com/insightvm/aws-security-hub/)

## RSA – RSA Archer \(Receives findings\)<a name="integration-rsa-archer"></a>

**Integration type:** Receive

RSA Archer IT and Security Risk Management allows you to determine which assets are critical to your business, establish and communicate security policies and standards, detect and respond to attacks, identify and remediate security deficiencies, and establish clear IT risk management best practices\.

[Product link](https://community.rsa.com/docs/DOC-111898)

[Partner documentation](https://community.rsa.com/docs/DOC-111898)

## SecureCloudDB – SecureCloudDB \(Sends findings\)<a name="integration-secureclouddb"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/secureclouddb/secureclouddb`

SecureCloudDB is a cloud native database security tool that provides comprehensive visibility of internal and external security postures and activity\. It flags security violations and provides remediation on exploitable database vulnerabilities\.

[Product link](http://aws.amazon.com/marketplace/pp/B08P2HR2Z7)

[Partner documentation](https://help.secureclouddb.com/guide/aws/security_hub.html)

## SentinelOne \(Sends findings\)<a name="integration-sentinelone"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/sentinelone/endpoint-protection`

SentinelOne is an autonomous extended detection and response \(XDR\) platform encompassing AI\-powered prevention, detection, response, and hunting across endpoints, containers, cloud workloads, and IoT devices\.

[AWS Marketplace link](http://aws.amazon.com/marketplace/pp/prodview-2qxvr62fng6li?sr=0-2&ref_=beagle&applicationId=AWSMPContessa)

[Partner documentation](https://support.sentinelone.com/hc/en-us/articles/4412384322711-Marketplace-Overview)

[Product link](https://www.sentinelone.com/sentinelone-for-aws/)

## ServiceNow – ITSM \(Receives and updates findings\)<a name="integration-servicenow-itsm"></a>

**Integration type:** Receive and update

The ServiceNow integration with Security Hub allows security findings from Security Hub to be viewed within ServiceNow ITSM\. You can also configure ServiceNow to automatically create an incident or problem when it receives a finding from Security Hub\.

Any updates to these incidents and problems result in updates to the findings in Security Hub\.

For an overview of the integration and how it works, watch the video [AWS Security Hub \- Bidirectional integration with ServiceNow ITSM](https://www.youtube.com/watch?v=OYTi0sjEggE)\.

[Product link](https://docs.aws.amazon.com/servicecatalog/latest/adminguide/integrations-servicenow.html)

[Partner documentation](https://docs.aws.amazon.com/servicecatalog/latest/adminguide/securityhub-config.html)

## Slack – Slack \(Receives findings\)<a name="integration-slack"></a>

**Integration type:** Receive

Slack is a layer of the business technology stack that brings together people, data, and applications\. It is a single place where people can effectively work together, find important information, and access hundreds of thousands of critical applications and services to do their best work\.

[Product link](https://github.com/aws-samples/aws-securityhub-to-slack)

[Partner documentation](https://docs.aws.amazon.com/chatbot/latest/adminguide/related-services.html)

## Sonrai Security – Sonrai Dig \(Sends findings\)<a name="integration-sonrai-dig"></a>

**Integration type:** Send

**Product ARN:** arn:aws:securityhub:*<REGION>*::product/sonrai\-security/sonrai\-dig

Sonrai Dig monitors and remediates cloud misconfigurations and policy violations, so you can improve your security and compliance posture\.

[Product link](https://sonraisecurity.com/solutions/amazon-web-services-aws-and-sonrai-security/)

[Partner documentation](https://sonraisecurity.com/blog/monitor-privilege-escalation-risk-of-identities-from-aws-security-hub-with-integration-from-sonrai/)

## Sophos – Server Protection \(Sends findings\)<a name="integration-sophos-server-protection"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:062897671886:product/sophos/sophos-server-protection`

Sophos Server Protection defends the critical applications and data at the core of your organization, using comprehensive defense\-in\-depth techniques\.

[Product link](https://www.sophos.com/en-us/lp/aws-security-hub-integration.aspx)

[Partner documentation](https://support.sophos.com/support/s/article/KB-000036466?language=en_US)

## Splunk – Splunk Enterprise \(Receives findings\)<a name="integration-splunk-enterprise"></a>

**Integration type:** Receive

**Product ARN:** `arn:aws:securityhub:<REGION>:112543817624:product/splunk/splunk-enterprise`

Splunk uses Amazon CloudWatch Events as a consumer of Security Hub findings\. Send your data to Splunk for advanced security analytics and SIEM\.

[Product link](https://www.splunk.com/en_us/form/stay-afloat-using-aws-security-hub.html)

[Partner documentation](https://github.com/splunk/splunk-for-securityHub)

## Splunk – Splunk Phantom \(Receives findings\)<a name="integration-splunk-phantom"></a>

**Integration type:** Receive

With the Splunk Phantom application for AWS Security Hub, findings are sent to Phantom for automated context enrichment with additional threat intelligence information or to perform automated response actions\.

[Product link](https://www.splunk.com/en_us/form/stay-afloat-using-aws-security-hub.html)

[Partner documentation](https://splunkphantom.s3.amazonaws.com/phantom-sechub-setup.html)

## StackRox – StackRox Kubernetes Security \(Sends findings\)<a name="integration-stackrox-kubernetes-security"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/stackrox/kubernetes-security`

StackRox helps enterprises secure their container and Kubernetes deployments at scale by enforcing their compliance and security policies across the entire container life cycle – build, deploy, and run\.

[Product link](http://aws.amazon.com/marketplace/pp/B07RP4B4P1)

[Partner documentation](https://help.stackrox.com/docs/integrate-with-other-tools/integrate-with-aws-security-hub/)

## Sumo Logic – Machine Data Analytics \(Sends findings\)<a name="integration-sumologic-machine-data-analytics"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:956882708938:product/sumologicinc/sumologic-mda`

Sumo Logic is a secure, machine data analytics platform that enables development and security operations teams to build, run, and secure their AWS applications\.

[Product link](https://www.sumologic.com/application/aws-security-hub/)

[Partner documentation](https://help.sumologic.com/07Sumo-Logic-Apps/01Amazon_and_AWS/AWS_Security_Hub)

## Symantec – Cloud Workload Protection \(Sends findings\)<a name="integration-symantec-cloud-workload-protection"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:754237914691:product/symantec-corp/symantec-cwp`

Cloud Workload Protection provides complete protection for your Amazon EC2 instances with antimalware, intrusion prevention, and file integrity monitoring\.

[Product link](https://www.broadcom.com/products/cyber-security/endpoint/hybrid-cloud/cloud-workload-protection)

[Partner documentation](https://help.symantec.com/cs/scwp/SCWP/v130271667_v111037498/Intergration-with-AWS-Security-Hub/?locale=EN_US&sku=CWP_COMPUTE)

## Sysdig – Sysdig Secure for cloud \(Sends findings\)<a name="integration-sysdig-secure"></a>

**Integration type:** Send

**Product ARN:** arn:aws:securityhub:*<REGION>*::product/sysdig/sysdig\-secure\-for\-cloud

Sysdig Secure for cloud supports asset discovery, risk management, Cloud Security Posture Management \(CSPM\), compliance, automatic vulnerability scanning for Amazon Elastic Container Registry \(ECR\) and Fargate, and threat detection based on CloudTrail\. You can deploy all of these as a single security platform\.

[Product link](https://cloudsec.sysdig.com/aws/)

[Partner documentation](https://cloudsec.sysdig.com/aws/security_hub)

## Tenable – Tenable\.io \(Sends findings\)<a name="integration-tenable-tenableio"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>:422820575223:product/tenable/tenable-io`

Accurately identify, investigate, and prioritize vulnerabilities\. Managed in the cloud\.

[Product link](https://www.tenable.com/)

[Partner documentation](https://github.com/tenable/Security-Hub)

## ThreatModeler \(Receives findings\)<a name="integration-threatmodeler"></a>

**Integration type:** Receive

ThreatModeler is an automated threat modeling solution that secures and scales the enterprise software and cloud development life cycle\.

[Product link](https://aws.amazon.com/marketplace/pp/B07S65ZLPQ)

[Partner documentation](https://threatmodeler-setup-quickstart.s3.amazonaws.com/ThreatModeler+Setup+Guide/ThreatModeler+Setup+%26+Deployment+Guide.pdf)

## Turbot – Turbot \(Sends and receives findings\)<a name="integration-turbot"></a>

**Integration type:** Send and receive

**Product ARN:** `arn:aws:securityhub:<REGION>:453761072151:product/turbot/turbot`

Turbot ensures that your cloud infrastructure is secure, compliant, scalable, and cost optimized\.

[Product link](https://turbot.com/features/)

[Partner documentation](https://turbot.com/blog/2018/11/aws-security-hub/)

## Vectra AI – Cognito Detect \(Sends findings\)<a name="integration-vectra-ai-cognito-detect"></a>

**Integration type:** Send

**Product ARN:** `arn:aws:securityhub:<REGION>::product/vectra-ai/cognito-detect`

Vectra is transforming cybersecurity by applying advanced AI to detect and respond to hidden cyberattackers before they can steal or cause damage\.

[AWS Marketplace link](http://aws.amazon.com/marketplace/pp/prodview-x2mabtjqsjb2w)

[Partner documentation](https://cognito-resource-guide.s3.us-west-2.amazonaws.com/Vectra_AWS_SecurityHub_Integration_Guide.pdf)