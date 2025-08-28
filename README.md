<h1>Real-Time Container Performance Monitoring with Prometheus, cAdvisor, and Grafana</h1>


<h2>Description</h2>
Built a real-time monitoring setup for Docker containers using Prometheus for metrics collection, cAdvisor as the metrics exporter, and Grafana for visualization. Designed dashboards to track CPU, memory, network, and disk usage for proactive performance analysis and quick issue detection. <br />


<h2>Tools and Technologies</h2>

- Docker
- Prometheus
- cAdvisor
- Grafana
- Linux (Ubuntu 24.04)
- Bash Scripting

<h2>Project Walk-through</h2>

<p align="center">
Deployed multiple Docker containers as the workload <br />
<img src="https://i.postimg.cc/wByDDkrC/c.jpg"/>
<br />
<br />
Monitored baseline performance using the docker stats command <br/>
<img src="https://i.postimg.cc/mD3zSpy5/d.jpg" />
<br />
<br />
Set up cAdvisor to export container-level metrics <br/>
<img src="https://i.postimg.cc/CKkzFrXx/f.jpg" />
<br />
<br />
Configured Prometheus to scrape metrics from cAdvisor <br/>
<img src="https://i.postimg.cc/mk2DyLDP/g.jpg" />
<br />
<br />
Integrated Grafana to build dashboards for visualization and analysis <br/>
<img src="https://i.postimg.cc/sfw1Dh67/h.jpg" />
<br />
<br />

</p>

