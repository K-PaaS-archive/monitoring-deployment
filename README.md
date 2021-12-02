## Related Repositories

<table>
  <tr>
    <td colspan=2 align=center>플랫폼</td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/paasta-deployment">어플리케이션 플랫폼</a></td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/paas-ta-container-platform">컨테이너 플랫폼</a></td>
  </tr>
  <tr>
    <td colspan=2 rowspan=2 align=center>포털</td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/portal-deployment">AP 포털</a></td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/container-platform-portal-release">CP 포털</a></td>
  </tr>
  <tr align=center>
    <td colspan=4><a href="https://github.com/PaaS-TA/monitoring-dashboard-source">모니터링 대시보드</a></td>
  </tr>
  <tr align=center>
    <td rowspan=2 colspan=2>🚩 <a href="https://github.com/PaaS-TA/monitoring-deployment">모니터링</a></td>
    <td><a href="https://github.com/PaaS-TA/monitoring-dashboard-release">Monitoring</a></td>
    <td><a href="https://github.com/PaaS-TA/monitoring-logsearch-release">Logsearch</a></td>
    <td><a href="https://github.com/PaaS-TA/monitoring-influxdb-release">InfluxDB</a></td>
    <td><a href="https://github.com/PaaS-TA/monitoring-redis-release">Redis</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/monitoring-pinpoint-release">Pinpoint</td>
    <td><a href="https://github.com/PaaS-TA/monitoring-pinpoint-buildpack">Pinpoint Buildpack</td>
    <td><a href="https://github.com/PaaS-TA/monitoring-zabbix-release">Zabbix</a></td>
    <td></td>
  </tr>
  </tr>
  <tr align=center>
    <td rowspan=4 colspan=2><a href="https://github.com/PaaS-TA/service-deployment">AP 서비스</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-CUBRID-RELEASE">Cubrid</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-API-GATEWAY-SERVICE-RELEASE">Gateway</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-GLUSTERFS-RELEASE">GlusterFS</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-APP-LIFECYCLE-SERVICE-RELEASE">Lifecycle</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-LOGGING-SERVICE-RELEASE">Logging</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-MONGODB-SHARD-RELEASE">MongoDB</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-MYSQL-RELEASE">MySQL</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-PINPOINT-RELEASE">Pinpoint APM</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-DELIVERY-PIPELINE-RELEASE">Pipeline</a></td>
    <td align=center><a href="https://github.com/PaaS-TA/rabbitmq-release">RabbitMQ</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-ON-DEMAND-REDIS-RELEASE">Redis</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-SOURCE-CONTROL-RELEASE">Source Control</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-WEB-IDE-RELEASE-NEW">WEB-IDE</a></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr align=center>
    <td rowspan=1 colspan=2><a href="https://github.com/PaaS-TA/paas-ta-container-platform-deployment">CP 서비스</a></td>
    <td><a href="https://github.com/PaaS-TA/container-platform-pipeline-release">Pipeline</a></td>
    <td><a href="https://github.com/PaaS-TA/container-platform-source-control-release">Source Control</a></td>
    <td></td>
    <td></td>
  </tr>
</table>
<i>🚩 You are here.</i>

# PaaS-TA Monitoring Install Guide


### │ PaaS-TA Monitoring Install Process


#### ⛤ ─ *Essential Installation.*  
- 아래에 나열된 순서대로 설치를 권장한다.

　 [[IaaS] Infrastructure Monitoring - Zabbix 설치](#) : IaaS 모니터링을 이용할 경우에만 설치  
 　　▸ [Zabbix Server 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_ZABBIX-SERVER_INSTALL.md)  
 　　▸ [Zabbix Proxy 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_ZABBIX-PROXY_INSTALL.md)  
 　　▸ [Zabbix Agent 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_ZABBIX-AGENT_INSTALL.md)  
   1. [BOSH (+Monitoring Dashboard) 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_BOSH2_MONITORING_INSTALL_GUIDE.md) ⛤   
   2. [PaaS-TA (+Monitoring Dashboard) 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_CORE_MONITORING_INSTALL_GUIDE.md) ⛤   
   3. [**Monitoring Dashboard** 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_PAAS-TA_MONITORING_INSTALL.md) ⛤ 
   4. [[PaaS] Log Monitoring - Logsearch 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_LOGSEARCH_INSTALL.md)  
   5. [[SaaS] Application Monitoring - Pinpoint Monitoring 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_PINPOINT_MONITORING_INSTALL.md)  
   6. [[CaaS] Container Monitoring - Prometheus 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_CONTAINER_SERVICE_INSTALL.md)  

- Zabbix 설치는 IaaS 모니터링 기능을 활성화할 경우 반드시 설치되어야 하며, 가장 먼저 설치하는 것을 권장하고 있다.
- Zabbix Agent는 배포과정에서 자동으로 설치되므로 [Zabbix Agent 설치](https://github.com/PaaS-TA/monitoring-guide/blob/master/install/PAAS-TA_MONITORING_ZABBIX-AGENT_INSTALL.md)  메뉴얼은 수동 설치시에만 참고한다.

<table>
  <tr>
    <td>⚠️ <b>PaaS-TA 플랫폼</b>에서 모니터링 기능(대시보드)을 사용할 경우, 반드시 <b>BOSH</b>와 <b>PaaS-TA</b> 배포 시에 모니터링에 필요한 옵션을 사용한 배포 작업이 필수 선행되어야 한다(#1, #2 설치 가이드 참고).</td>
  </tr>
</table>

## Contributors ✨
Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/hsohans"><img src="https://avatars.githubusercontent.com/u/51317201?v=4" width="100px;" alt=""/><br /><sub><b>hso</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/RomulusKim"><img src="https://avatars.githubusercontent.com/u/73581918?v=4" width="100px;" alt=""/><br /><sub><b>Romulus Kim</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/thouy"><img src="https://avatars.githubusercontent.com/u/32118423?v=4" width="100px;" alt=""/><br /><sub><b>Minsoo, Kim</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/thansrb"><img src="https://avatars.githubusercontent.com/u/31251109?v=4" width="100px;" alt=""/><br /><sub><b>thansrb</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/okpc579"><img src="https://avatars.githubusercontent.com/u/55691511?v=4" width="100px;" alt=""/><br /><sub><b>Ruby</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/taking"><img src="https://avatars.githubusercontent.com/u/9063986?v=4" width="100px;" alt=""/><br /><sub><b>taking</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/jhuhm135"><img src="https://avatars.githubusercontent.com/u/70005316?v=4" width="100px;" alt=""/><br /><sub><b>jhuhm135</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/YoongJwe"><img src="https://avatars.githubusercontent.com/u/78844504?v=4" width="100px;" alt=""/><br /><sub><b>YoongJwe</b></sub></a><br /><a href="#" title="Code">💻</a> <a href="#" title="Reviewed Pull Requests">👀</a></td>
  </tr>
</table>
