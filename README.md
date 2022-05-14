<div align='center'>
  
# Security Operations Center Platform 
  
🌊 Building a platform based on opensource solutions for security operation center


![image](https://user-images.githubusercontent.com/32587640/168414090-e7b2ed23-f8dc-414e-8b0d-7cc341cf7e42.png)
  
</div>

## Index

* [General architecture of platform](https://github.com/kh-elbrus/soc-platform#general-architecture)
* [Workflow](https://github.com/kh-elbrus/soc-platform#workflow)
* [Application from diagram](https://github.com/kh-elbrus/application-from-diagram)
* [Investigation tools](https://github.com/kh-elbrus/investigation-tools)
* [Incident Response playbooks](https://github.com/kh-elbrus/incident-response-playbooks)
* [API integrations for analysis](https://github.com/kh-elbrus/api-integrations-for-analysis)
* [Installation guides](https://github.com/kh-elbrus/soc-platform#installation-guides)

---

## General architecture

![General diagram](https://user-images.githubusercontent.com/32587640/168418076-07d4b9b3-5713-41d1-953f-ea2871ac6849.jpg)

## Workflow

// TODO: add workflow diagram 

## Application from diagram  

|   №   |             ⚡ Tool             |                                                 🙌 Link                                                 |
| :---: | :----------------------------: | :----------------------------------------------------------------------------------------------------: |
|   1   |         Elasticsearch          | [checkout](https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html) |
|   2   |             Kibana             |                [checkout](https://www.elastic.co/guide/en/kibana/current/install.html)                 |
|   3   |            Logstash            |         [checkout](https://www.elastic.co/guide/en/logstash/current/installing-logstash.html)          |
|   4   |       OpenDistro plugins       |         [checkout](https://opendistro.github.io/for-elasticsearch-docs/docs/install/plugins/)          |
|   5   |             Redis              |                                     [checkout](https://redis.io/)                                      |
|   6   |          MITRE ATT&CK          |                                 [checkout](https://attack.mitre.org/)                                  |
|   7   |           ElastAlert           |                             [checkout](https://github.com/Yelp/elastalert)                             |
|   8   |            Jupyter             |                                    [checkout](https://jupyter.org/)                                    |
|   9   | Jupyter threat hunter playbook |            [checkout](https://threathunterplaybook.com/tutorials/jupyter/introduction.html)            |
|  10   |            TheHive             |                         [checkout](https://github.com/TheHive-Project/TheHive)                         |
|  11   |             Cortex             |                         [checkout](https://github.com/TheHive-Project/Cortex)                          |
|  12   |              MISP              |                                [checkout](https://github.com/MISP/MISP)                                |
|  13   |          MISP modules          |                            [checkout](https://github.com/MISP/misp-modules)                            |
|  14   |             GitLab             |                             [checkout](https://about.gitlab.com/install/)                              |
|  15   |            Grafana             |                                    [checkout](https://grafana.com/)                                    |
|  16   |           Prometheus           |                                   [checkout](https://prometheus.io/)                                   |
|  17   |              Jira              |                         [checkout](https://www.atlassian.com/ru/software/jira)                         |
|  18   |             Teams              |            [checkout](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software)             |
|  19   |             Slack              |                                     [checkout](https://slack.com/)                                     |
|  20   |             Sigma              |                              [checkout](https://github.com/SigmaHQ/sigma)                              |
|  21   |             Wazuh              |                                     [checkout](https://wazuh.com/)                                     |
|  22   |             Nessus             |                 [checkout](https://www.tenable.com/products/nessus/nessus-essentials)                  |
|  23   |           Red Canary           |                       [checkout](https://github.com/redcanaryco/atomic-red-team)                       |
|  24   |             Beats              |                               [checkout](https://www.elastic.co/beats/)                                |
|  25   |             Sysmon             |               [checkout](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon)               |
|  26   |             Cowrie             |                              [checkout](https://github.com/cowrie/cowrie)                              |
|  27   |          StreamAlert           |                           [checkout](https://github.com/airbnb/streamalert)                            |

## Investigation tools 

|   №   |      ⚡ Tool      |                          🙌 Link                          |
| :---: | :--------------: | :------------------------------------------------------: |
|   1   |     ChainSaw     |   [checkout](https://github.com/countercept/chainsaw)    |
|   2   |   LogonTracer    |   [checkout](https://github.com/JPCERTCC/LogonTracer)    |
|   3   |    APT-Hunter    |  [checkout](https://github.com/ahmedkhlief/APT-Hunter)   |
|   4   |     Backstab     |      [checkout](https://github.com/Yaxser/Backstab)      |
|   5   |      TheZoo      |       [checkout](https://github.com/ytisf/theZoo)        |
|   6   | Invoke-Forensics | [checkout](https://github.com/swisscom/Invoke-Forensics) |


## Incident Response playbooks 

|   №   |                       ⚡ Tool                       |                                          🙌 Link                                           |
| :---: | :------------------------------------------------: | :---------------------------------------------------------------------------------------: |
|   1   |       Microsoft Incident response playbooks        | [checkout](https://docs.microsoft.com/en-us/security/compass/incident-response-playbooks) |
|   2   |        Public Incident Response Ressources         |                    [checkout](https://gitlab.com/syntax-ir/playbooks)                     |
|   3   |                     Playbooks                      |                  [checkout](https://www.incidentresponse.com/playbooks/)                  |
|   4   |          aws-incident-response-playbooks           |        [checkout](https://github.com/aws-samples/aws-incident-response-playbooks)         |
|   5   | Incident Response Playbooks Mapped to MITRE Attack |               [checkout](https://github.com/austinsonger/Incident-Playbook)               |

## API integrations for analysis 

|   №   |     ⚡ Service     | 🙌 Status  |
| :---: | :---------------: | :-------: |
|   1   |    Virustotal     | `not yet` |
|   2   |      Shodan       | `not yet` |
|   3   |      Censys       | `not yet` |
|   4   |  Security Trails  | `not yet` |
|   5   |    IBM XForce     | `not yet` |
|   6   |  AlienVault OTX   | `not yet` |
|   7   | have i been pwned | `not yet` |
|   8   |     LeakCheck     | `not yet` |


---

## Installation guides

* [Requirements](./installation/requirements.md)
* [Network rules](./installation/network-rules.md)
* [Stage 1. Terraform | Build infrastructure](./installation/stage-1/terraform.md)




---

