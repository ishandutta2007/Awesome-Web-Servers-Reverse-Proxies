# Awesome-Web-Servers-Reverse-Proxies

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Web-Servers-Reverse-Proxies

# Top Web Servers & Reverse Proxies Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on HTTP Servers, Reverse Proxying, TLS Termination, Edge CDN Delivery & Application Gateways*  
**Last updated: October 2026**

This repository tracks notable **SaaS/CDN platforms** and **open-source projects** for **Web Servers & Reverse Proxies**. These systems terminate TLS, route traffic, cache content, and front application backends at the edge or in your data center.

**Examples** include Cloudflare, Fastly, Akamai, AWS CloudFront, F5 NGINX Plus, Imperva, Sucuri, KeyCDN, StackPath, and **Caddy** (`caddyserver/caddy`)—a fast, multi-platform HTTP/1–2–3 web server with automatic HTTPS.

**Open-source emphasis**: Origin and edge software is dominated by open source. **Nginx**, **Caddy**, **Traefik**, **HAProxy**, **Apache httpd**, **Envoy**, and **Varnish** power a large share of the public web. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cloudflare, Fastly, Akamai, AWS CloudFront](https://www.cloudflare.com/)**  
  Global CDN and edge platforms—caching, DDoS protection, TLS, and programmable edge logic at massive scale.

- **[F5 NGINX Plus, Imperva, Sucuri](https://www.nginx.com/)**  
  Commercial application delivery, WAF, and security-focused proxy offerings (NGINX Plus is the commercial edition of open Nginx).

- **[KeyCDN, StackPath, other regional CDNs](https://www.keycdn.com/)**  
  Content delivery and edge security services for mid-market and specialized workloads.

- **[Other managed edge & ADC platforms](https://aws.amazon.com/cloudfront/)**  
  Additional cloud load balancers and reverse-proxy-as-a-service products.

## Open-Source GitHub Projects

### Web Servers & General-Purpose Proxies

- **[Caddy](https://github.com/caddyserver/caddy)**  
  Fast, multi-platform open web server with automatic HTTPS (Let's Encrypt by default), HTTP/1–2–3, and a simple configuration model.

- **[Nginx](https://github.com/nginx/nginx)**  
  Ubiquitous open web server and reverse proxy—high performance, rich module ecosystem, and the foundation of many commercial ADCs.

- **[Apache HTTP Server](https://github.com/apache/httpd)**  
  Long-standing open web server with flexible modules, virtual hosting, and broad platform support.

- **[Traefik](https://github.com/traefik/traefik)**  
  Open cloud-native reverse proxy and load balancer—automatic service discovery for Kubernetes, Docker, and dynamic backends.

- **[HAProxy](https://github.com/haproxy/haproxy)**  
  High-performance open TCP/HTTP load balancer and reverse proxy—legendary reliability for layer 4 and layer 7 routing.

- **[Envoy](https://github.com/envoyproxy/envoy)**  
  Open edge and service proxy designed for cloud-native apps—L7 features, observability, and the data plane for many meshes.

### Caching, Edge & Specialized Proxies

- **[Varnish Cache](https://github.com/varnishcache/varnish-cache)**  
  Open HTTP accelerator focused on caching—widely used in front of origin servers for dynamic and static content.

- **[OpenResty](https://github.com/openresty/openresty)**  
  Nginx core bundled with LuaJIT—scriptable reverse proxy and application gateway patterns.

- **[Squid](https://github.com/squid-cache/squid)**  
  Open caching proxy for web and related protocols—still used for forward and reverse proxy scenarios.

- **[Pomerium / oauth2-proxy](https://github.com/pomerium/pomerium)**  
  Open identity-aware proxies for securing internal apps with modern SSO.

- **[Caddy + CrowdSec / security modules](https://github.com/caddyserver/caddy)**  
  Patterns combining open servers with open security tooling at the edge.

- **[Ats (Apache Traffic Server)](https://github.com/apache/trafficserver)**  
  Open fast, scalable caching proxy server used by large content providers.

### Additional Strong Open-Source Options

- **Simple automatic HTTPS**: Caddy.
- **Maximum deployment familiarity**: Nginx.
- **Cloud-native ingress**: Traefik or Envoy-based gateways.
- **Pure load balancing**: HAProxy.
- **HTTP caching**: Varnish.
- **Composable stacks**: Caddy/Nginx/Traefik → app servers; or CDN (Cloudflare/Fastly) → origin (Nginx/Caddy).
- Global CDN SaaS still leads for anycast PoPs, volumetric DDoS absorption, and managed WAF rulesets.

**Frameworks for building custom systems**:  
**Caddy** for automatic TLS and modern defaults; **Nginx** or **HAProxy** for battle-tested proxying; **Traefik** / **Envoy** for dynamic cloud-native routing; **Varnish** for caching layers.  
Fully open origin and reverse-proxy stacks are the industry norm; CDNs complement them at the edge.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Reverse proxies and edge servers are high-value attack targets. Keep software updated, restrict admin interfaces, configure TLS carefully, and rate-limit aggressively. Misconfigured proxies can expose internal services.
- Open-source servers offer full control and transparency. Commercial CDNs and ADCs shift global capacity and managed security to the vendor. Neither replaces secure application design and least-privilege networking.

---

**Made for platform engineers, SREs, and anyone putting HTTP services on the internet.**  
Let's expand open web servers and proxies while recognizing the global edge scale that leading CDN platforms deliver.
