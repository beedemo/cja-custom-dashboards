# cja-custom-dashboards
CloudBees Jenkins Analytics Custom Kibana Dashboards

- Audit Trail: Utilized data collected from the [Audit Trail plugin](https://wiki.jenkins-ci.org/display/JENKINS/Audit+Trail+Plugin) to display analytics around who performed certain Jenkins configuration operations on CJOC and connected masters.
- Deployments: Utilizes a custom [Pipeline shared library](https://github.com/beedemo/workflowLibs/blob/master/vars/deployAnalytics.groovy) to collect information around deployments from Jenkins masters.
