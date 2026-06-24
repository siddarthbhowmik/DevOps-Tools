# DevOps-Tools

This repository provides the list of tools that are opensource, free or paid in nature and helps you implement Cloud/DevOps process framework for any individual or at enterprise level.

---

## What is DevOps?

DevOps is the practice of operations and development engineers participating together in the entire service lifecycle, from design through the development process to production support. [Wiki - DevOps](https://en.wikipedia.org/wiki/DevOps)

---

## Tools

Below are the indexes that list the tools available as per their work areas.

- [Contents](#contents)
  - [API Gateway](#api-gateway)
  - [Automation Platforms](#automation-platforms)
  - [Cloud Platforms](#cloud-platforms)
  - [Containers Platforms](#containers-platforms)
  - [Continuous Integration and Delivery](#continuous-integration-and-delivery)
  - [FinOps & Cost Management](#finops--cost-management)
  - [GitOps & Progressive Delivery](#gitops--progressive-delivery)
  - [Incident Management](#incident-management)
  - [Internal Developer Platforms](#internal-developer-platforms)
  - [Messaging Queue](#messaging-queue)
  - [Monitoring & Observability](#monitoring--observability)
  - [Operating Systems](#operating-systems)
  - [Programming Languages](#programming-languages)
  - [Security & Compliance (DevSecOps)](#security--compliance-devsecops)
  - [Service Mesh & Networking](#service-mesh--networking)
  - [Source Control Management](#source-control-management)

---

## API Gateway

- [Ambassador](https://www.getambassador.io/) - Ambassador is an API Gateway for cloud-native applications that routes traffic between heterogeneous services and maintains decentralized workflows.
- [API Umbrella](https://apiumbrella.io/#) - API Umbrella is a proxy that sits in front of your APIs.
- [Cilium](https://github.com/cilium/cilium) - Cilium is open source software for providing and transparently securing network connectivity and loadbalancing between application workloads.
- [Envoy](https://www.envoyproxy.io/) - Envoy is an open source edge and service proxy, designed for cloud-native applications.
- [Gloo](https://www.gloo.us/) - Gloo Mesh is an enhanced Envoy Proxy API gateway for Kubernetes (K8s) Ingress to secure microservices application traffic at the edge.
- [Kong](https://konghq.com/) - Kong is Orchestration Microservice API Gateway. Kong is a Lua application running in Nginx and made possible by the lua-nginx-module.
- [Nginx](https://nginx.org/) - The NGINX Plus API gateway authenticates API calls, routes requests to appropriate backends, applies rate limits to prevent overloading services and to mitigate DDoS attacks, offloads SSL/TLS traffic to improve performance, and handles errors and exceptions.
- [Traefik](https://traefik.io/) - Traefik exposes a number of information through an API handler, such as the configuration of all routers, services, middlewares, etc.
- [Tyk](https://tyk.io/) - Performant and secure, Tyk API management offers a secure API gateway for your API and microservices.
- [APISIX](https://apisix.apache.org/) - Apache APISIX is a dynamic, real-time, high-performance open source API gateway, providing rich traffic management features such as load balancing, dynamic upstream, canary release, service circuit breaker, authentication, and observability.
- [Krakend](https://www.krakend.io/) - KrakenD is a stateless, distributed, high-performance API Gateway that helps you effortlessly adopt microservices, reducing response times by creating a layer that aggregates data from multiple systems.

---

## Automation Platforms

- [Ansible](https://www.ansible.com/) - Ansible is an open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code.
- [Atlantis](https://www.runatlantis.io/) - Atlantis is an open source tool that allows safe collaboration on Terraform projects by making sure that proposed changes are reviewed and that the proposed change is the actual change which will be executed on your infrastructure.
- [Bosh](https://bosh.io/docs/) - BOSH is a project that unifies release engineering, deployment, and lifecycle management of small and large-scale cloud software.
- [Capistrano](https://capistranorb.com/) - Capistrano is a remote server automation tool.
- [Chef](https://www.chef.io/) - Chef is a company and the name of a configuration management tool written in Ruby and Erlang.
- [Cloudify](https://cloudify.co/) - Cloudify is an open source application and network services orchestration framework based on TOSCA, for award winning edge networking.
- [Fabric](http://www.fabfile.org/) - Fabric is a Python library and command-line tool for streamlining the use of SSH for application deployment or systems administration tasks.
- [Foreman](https://theforeman.org/) - Foreman is an open source complete life cycle systems management tool for provisioning, configuring and monitoring of physical and virtual servers.
- [Juju](https://jaas.ai/) - Juju enables you to encapsulate each different part of your infrastructure and lets everything talk to each other.
- [ManageIQ](https://www.manageiq.org/) - Continuous Discovery. Connect ManageIQ to your virtualization, container, network, and storage management systems, where it will discover inventory, map relationships, and listen for changes.
- [Mina](http://nadarei.co/mina/) - Mina lets you build and run scripts to manage your app deployments on servers via SSH.
- [Nomad](https://www.nomadproject.io/) - Nomad is a flexible workload orchestrator that enables an organization to easily deploy and manage any containerized or legacy application using a single, unified workflow.
- [OctoDNS](https://github.com/github/octodns) - OctoDNS provides a set of tools & patterns that make it easy to manage your DNS records across multiple providers.
- [OpenTofu](https://opentofu.org/) - OpenTofu is the open-source, community-driven fork of Terraform, maintained under the Linux Foundation. It stays compatible with most Terraform workflows and adds state encryption and a separate provider registry.
- [Packer](https://www.packer.io/) - Packer is a free and open source tool for creating golden images for multiple platforms from a single source configuration.
- [Pulumi](https://www.pulumi.com/) - Pulumi is an open source infrastructure as code tool that allows you to use familiar programming languages (Python, TypeScript, Go, etc.) to define and manage cloud infrastructure.
- [Puppet](https://puppet.com/) - Puppet is a software configuration management tool which includes its own declarative language to describe system configuration.
- [Rundeck](https://www.rundeck.com/) - Rundeck is an open-source tool that helps to define build, deploy and manage automation.
- [Salt](https://saltproject.io/) - SaltStack is a Python-based open source configuration management and remote execution application.
- [StackStorm](https://stackstorm.com/) - StackStorm connects all your apps, services, and workflows.
- [Terraform](https://www.terraform.io/) - Terraform is an infrastructure as code (IaC) tool that allows you to build, change, and version infrastructure safely and efficiently. Now owned by IBM (acquired HashiCorp in February 2025) and licensed under the Business Source License (BSL).
- [Vagrant](https://www.vagrantup.com/) - Vagrant is a tool for building and managing virtual machine environments in a single workflow.
- [env0](https://www.env0.com/) - env0 (formerly Env0) is a collaborative platform for managing IaC workflows supporting Terraform, OpenTofu, Pulumi, Ansible, and Helm, with policy enforcement and GitOps integration.

---

## Cloud Platforms

- [Alibaba Cloud](https://us.alibabacloud.com/) - Alibaba Cloud, founded in 2009, is a global leader in cloud computing and artificial intelligence, providing services to thousands of enterprises, developers, and governments organizations in more than 200 countries and regions.
- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Amazon Web Services (AWS) is the world's most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally.
- [Apache CloudStack](https://cloudstack.apache.org/) - Apache CloudStack is open source software designed to deploy and manage large networks of virtual machines, as a highly available, highly scalable Infrastructure as a Service (IaaS) cloud computing platform.
- [Azure](https://azure.microsoft.com/) - The Azure cloud platform provides more than 200 products and cloud services designed to help you bring new solutions to life.
- [DigitalOcean](https://www.digitalocean.com/) - DigitalOcean provides an inexpensive and easy-to-use cloud service that provides basic services in a well-designed environment.
- [Fly.io](https://fly.io/) - Fly.io is a platform for running full-stack apps and databases close to your users on hardware spread across 30+ regions.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - The Google Cloud Platform (GCP) is a platform that delivers over 90 information technology services (products) for businesses, IT professionals, and developers.
- [IBM Cloud](https://www.ibm.com/cloud) - IBM Cloud offers the most open and secure public cloud for business with a next-generation hybrid cloud platform, advanced data and AI capabilities, and deep enterprise expertise.
- [Linode / Akamai Cloud](https://www.linode.com/) - Akamai Cloud (formerly Linode) offers easily deployable cloud compute, storage, and networking with a full-featured API and CLI.
- [Localstack](https://github.com/localstack/localstack) - A fully functional local cloud stack. Develop and test your cloud and serverless apps offline.
- [OpenNebula](https://opennebula.org/) - OpenNebula is a powerful, but easy-to-use, open source platform to build and manage Enterprise Clouds.
- [OpenStack](https://www.openstack.org/) - OpenStack is an open source cloud computing infrastructure software project and is one of the three most active open source projects in the world.
- [Oracle Cloud](https://www.oracle.com/cloud/) - Oracle Cloud Infrastructure (OCI) is a deep and broad platform of public cloud services for building and running a wide range of applications.
- [Scaleway](https://www.scaleway.com/) - Scaleway is a high quality hosting and data storage company using cloud-based technology.
- [VMware Cloud / Broadcom](https://cloud.vmware.com/) - VMware Cloud (now under Broadcom) delivers a model of cloud operations for hybrid and multi-cloud environments.
- [Vultr](https://www.vultr.com/) - Vultr is on a mission to empower developers and businesses by simplifying the deployment of infrastructure via its advanced cloud platform.

---

## Containers Platforms

- [Buildah](https://buildah.io/) - Buildah is an open source tool for building OCI-compatible container images without requiring a daemon, and works well in rootless environments.
- [containerd](https://containerd.io/) - containerd is an industry-standard container runtime with an emphasis on simplicity, robustness, and portability. It is a CNCF graduated project.
- [Docker](https://www.docker.com/) - Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly.
- [Docker Compose](https://github.com/docker/compose) - Docker Compose is a tool for running multi-container applications on Docker defined using the Compose file format.
- [Dokku](http://dokku.viewdocs.io/dokku/) - Dokku is an extensible, open source Platform as a Service that runs on a single server of your choice.
- [gVisor](https://gvisor.dev/) - gVisor is an application kernel written in Go that implements a substantial portion of the Linux system call interface, providing an additional layer of isolation for containers.
- [K3S](https://k3s.io/) - K3s is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.
- [Kata Containers](https://katacontainers.io/) - Kata Containers is an open source community working to build a secure container runtime with lightweight virtual machines that feel and perform like containers, but provide stronger workload isolation.
- [Kubernetes](https://kubernetes.io/) - Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.
- [LXC](https://linuxcontainers.org/) - linuxcontainers.org is the umbrella project behind LXD, LXC, LXCFS and distrobuilder. The goal is to offer a distro and vendor neutral environment for the development of Linux container technologies.
- [OrbStack](https://orbstack.dev/) - OrbStack is a fast, light, and simple way to run Docker containers and Linux machines on macOS.
- [OpenShift](https://www.openshift.com/) - Red Hat® OpenShift® is an enterprise-ready Kubernetes container platform built for an open hybrid cloud strategy.
- [Podman](https://podman.io/) - Podman (the POD MANager) is a daemonless tool for managing containers and images, volumes mounted into those containers, and pods made from groups of containers.
- [Rancher](https://rancher.com/) - Rancher is an open source container management platform built for organizations that deploy containers in production.
- [Skaffold](https://skaffold.dev/) - Skaffold is a command-line tool from Google that handles the workflow for building, pushing, and deploying applications to Kubernetes continuously.
  - **Container Registry**
    - [Harbor](https://goharbor.io/) - Harbor is an open source registry that secures artifacts with policies and role-based access control, ensures images are scanned and free from vulnerabilities, and signs images as trusted.
    - [Quay](https://www.projectquay.io/) - Quay is a container image registry that enables you to build, organize, distribute, and deploy containers.
    - [Chainguard Images](https://www.chainguard.dev/chainguard-images) - Chainguard Images are minimal, hardened container images designed to reduce supply chain attack surface.
  - **Supply Chain Security**
    - [Cosign](https://github.com/sigstore/cosign) - Cosign is a tool for signing and verifying container images, part of the Sigstore project.
    - [Syft](https://github.com/anchore/syft) - Syft is a CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems.
    - [Sigstore](https://www.sigstore.dev/) - Sigstore is a free service for securing the software supply chain by providing tools for signing, verifying, and protecting open source software.

---

## Continuous Integration and Delivery

- [Argo CD](https://argoproj.github.io/cd/) - Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes.
- [Argo Workflows](https://argoproj.github.io/workflows/) - Open source tools for Kubernetes to run workflows, manage clusters, and do GitOps right.
- [Bamboo](https://www.atlassian.com/software/bamboo) - Bamboo Data Center is a continuous delivery pipeline that offers resilience, reliability, and scalability for teams of any size.
- [Bitrise](https://www.bitrise.io/) - Bitrise is a Continuous Integration and Delivery (CI/CD) Platform as a Service with a main focus on mobile app development (iOS, Android, React Native, Flutter, and so on).
- [Buildkite](https://buildkite.com/) - Buildkite is a platform for running fast, secure, and scalable continuous integration pipelines on your own infrastructure.
- [Circle CI](https://circleci.com/) - CircleCI's continuous integration and delivery platform helps software teams rapidly release code with confidence by automating the build, test, and deploy process.
- [Codefresh](https://codefresh.io/) - Codefresh is a Continuous Integration/Delivery solution that fetches code from your Git repository, packages/compiles it, and deploys the final artifact to a target environment.
- [Concourse](https://concourse-ci.org/) - Concourse CI is a system built with a loosely coupled microservices architecture.
- [Dagger](https://dagger.io/) - Dagger is a programmable CI/CD engine that runs pipelines in containers, allowing you to develop and run your CI/CD pipeline locally and on any CI platform.
- [Drone](https://github.com/drone/drone) - Drone is a continuous delivery system built on container technology. Drone uses a simple YAML build file, to define and execute build pipelines inside Docker containers.
- [Flux](https://fluxcd.io/) - Flux is a set of continuous and progressive delivery solutions for Kubernetes that are open and extensible. It is a CNCF graduated project.
- [Gitlab CI](https://about.gitlab.com/product/continuous-integration/) - GitLab CI/CD automates all the steps required to build, test and deploy your code to your production environment.
- [GitHub Actions](https://github.com/features/actions) - GitHub Actions makes it easy to automate all your software workflows, with world-class CI/CD. Build, test, and deploy your code right from GitHub.
- [goCD](https://www.gocd.org/) - GoCD is an open source continuous delivery server that helps organizations increase productivity and deliver high quality through automation.
- [Jenkins](http://jenkins-ci.org/) - Jenkins is an automation server written in Java that helps build, test, and continually deploy software.
- [PipeCD](https://pipecd.dev/) - PipeCD provides a unified continuous delivery solution for multiple application kinds on multi-cloud that empowers engineers to deploy faster with more confidence.
- [Spinnaker](https://www.spinnaker.io/) - Spinnaker provides application management and deployment to help you release software changes with high velocity and confidence.
- [Teamcity](https://www.jetbrains.com/teamcity/) - TeamCity is a build management and continuous integration server from JetBrains.
- [Tekton](https://tekton.dev/) - Tekton is a powerful yet flexible Kubernetes-native open source framework for creating continuous integration and delivery (CI/CD) systems.
- [Travis CI](https://travis-ci.org/) - Travis CI is a continuous integration tool that tests and deploys your projects with ease.
- [werf](https://werf.io/) - Consistent delivery tool. The CLI tool gluing Git, Docker, Helm & Kubernetes with any CI system to implement CI/CD and Giterminism.
- [Woodpecker CI](https://woodpecker-ci.org/) - Woodpecker is a community fork of Drone CI, providing a simple yet powerful CI/CD engine with native container support.

---

## FinOps & Cost Management

- [CloudHealth by VMware](https://cloudhealth.vmware.com/) - CloudHealth provides a unified platform for managing cloud cost, usage, security, and performance across AWS, Azure, and GCP.
- [Infracost](https://www.infracost.io/) - Infracost is an open source tool that shows cloud cost estimates for Terraform projects directly in pull requests.
- [Kubecost](https://www.kubecost.com/) - Kubecost provides real-time cost visibility and insights into Kubernetes environments, helping teams monitor, manage, and reduce their cloud spending.
- [OpenCost](https://www.opencost.io/) - OpenCost is a vendor-neutral open source CNCF project for measuring and allocating cloud infrastructure and container costs in real time.
- [Vantage](https://www.vantage.sh/) - Vantage is a cloud cost transparency platform that consolidates costs across AWS, Azure, GCP, and Kubernetes, offering reporting, budgets, and recommendations.

---

## GitOps & Progressive Delivery

- [Argo CD](https://argoproj.github.io/cd/) - Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes that keeps cluster state in sync with a Git repository.
- [Argo Rollouts](https://argoproj.github.io/rollouts/) - Argo Rollouts provides advanced deployment capabilities such as blue-green, canary, canary analysis, and progressive delivery to Kubernetes.
- [Flagger](https://flagger.app/) - Flagger is a progressive delivery tool that automates the release process for applications running on Kubernetes, supporting canary deployments and A/B testing.
- [Flux](https://fluxcd.io/) - Flux is a CNCF graduated GitOps tool that continuously reconciles cluster state with a Git repository, supporting Helm, Kustomize, and multi-tenancy.
- [Weave GitOps](https://www.weave.works/product/gitops/) - Weave GitOps extends Flux with a developer-friendly UI and enterprise features for large-scale GitOps workflows.

---

## Incident Management

- [Grafana OnCall](https://grafana.com/products/oncall/) - Grafana OnCall is an open source on-call management tool that integrates with Grafana for alert routing, escalation policies, and on-call scheduling.
- [Incident.io](https://incident.io/) - Incident.io is a modern incident management platform that streamlines the declaration, coordination, and review of incidents, with deep Slack integration.
- [OpsGenie](https://www.opsgenie.com/) - Opsgenie is a modern incident management platform that ensures critical incidents are never missed, and actions are taken by the right people in the shortest possible time.
- [PagerDuty](https://www.pagerduty.com/) - PagerDuty is an operations performance platform delivering visibility and actionable intelligence across the entire incident lifecycle.
- [PagerTree](https://pagertree.com/) - PagerTree on-call incident management gives DevOps teams flexible schedules, escalations, and reliable notifications via email, SMS, voice, and smartphone app.
- [Rootly](https://rootly.com/) - Rootly is an incident management platform that automates incident response workflows directly within Slack.
- [StatusPal](https://www.statuspal.io/) - StatusPal is a status page and incident communication platform for DevOps and SRE teams.
- [VictorOps / Splunk On-Call](https://victorops.com/) - VictorOps (now Splunk On-Call) is a real-time incident management platform that combines the power of people and data to embolden DevOps teams.

---

## Internal Developer Platforms

Internal Developer Platforms (IDPs) provide self-service infrastructure and tooling to development teams, reducing cognitive load and standardizing workflows.

- [Backstage](https://backstage.io/) - Backstage is an open source framework created by Spotify for building developer portals. It unifies all infrastructure tooling, services, and documentation in a single developer portal.
- [Cortex](https://www.cortex.io/) - Cortex is an Internal Developer Portal that helps engineering teams improve service quality, track ownership, and build golden paths.
- [Humanitec](https://humanitec.com/) - Humanitec is a platform orchestrator that enables platform engineering teams to build self-service developer platforms on top of any cloud or on-premises infrastructure.
- [Port](https://www.getport.io/) - Port is a developer portal that allows engineering teams to build a centralized catalog of their software and infrastructure resources.
- [Radius](https://radapp.io/) - Radius is an open source cloud-native application platform that enables developers and operators to define, deploy, and manage cloud-native applications across environments.
- [Kratix](https://kratix.io/) - Kratix is an open source framework for building platforms on Kubernetes, enabling platform teams to define APIs and enable self-service infrastructure for developers.

---

## Messaging Queue

- [ActiveMQ](http://activemq.apache.org/) - Apache ActiveMQ® is the most popular open source, multi-protocol, Java-based message broker.
- [Beanstalkd](https://beanstalkd.github.io/) - Beanstalk is a simple, fast work queue, originally designed for reducing the latency of page views in high-volume web applications by running time-consuming tasks asynchronously.
- [Celery](https://docs.celeryq.dev/) - Celery is an open source asynchronous task queue or job queue which is based on distributed message passing.
- [Faktory](https://github.com/contribsys/faktory) - Faktory is a work server and repository for background jobs within your application.
- [Kafka](http://kafka.apache.org/) - Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.
- [NATS](https://nats.io/) - NATS is a connective technology built for the hyper-connected world. It is a single technology that enables applications to securely communicate across any combination of cloud vendors, on-premise, edge, web and mobile, and devices.
- [NSQ](https://nsq.io/) - NSQ is a realtime distributed messaging platform designed to operate at scale, handling billions of messages per day.
- [Pulsar](https://pulsar.apache.org/) - Apache Pulsar is an open-source, distributed messaging and streaming platform built for the cloud, offering geo-replication, multi-tenancy, and tiered storage.
- [RabbitMQ](https://www.rabbitmq.com/) - RabbitMQ is a messaging broker that gives your applications a common platform to send and receive messages.
- [Redpanda](https://redpanda.com/) - Redpanda is a Kafka-compatible streaming platform for mission-critical workloads, written in C++ and designed for high-throughput, low-latency use cases without the JVM overhead.

---

## Monitoring & Observability

- [Alerta](https://github.com/alerta/alerta) - Alerta accepts alerts from the standard sources like Syslog, SNMP, Prometheus, Nagios, Zabbix, Sensu and netdata.
- [Cachet](https://github.com/CachetHQ/Cachet) - Cachet is a beautiful and powerful open source status page system.
- [cAdvisor](https://github.com/google/cadvisor) - cAdvisor (Container Advisor) provides container users an understanding of the resource usage and performance characteristics of their running containers.
- [Datadog](https://www.datadoghq.com/) - Datadog is an observability and security platform for cloud environments that includes infrastructure monitoring, APM, log management, security monitoring, and AI-powered anomaly detection.
- [Fluentd](https://www.fluentd.org/) - Fluentd is an open source data collector, which lets you unify the data collection and consumption for a better use and understanding of data.
- [Grafana](https://grafana.com/) - Grafana is an open source interactive data-visualization platform that allows users to see their data via charts and graphs unified into dashboards.
- [Grafana Loki](https://grafana.com/oss/loki/) - Loki is a horizontally scalable, highly available, multi-tenant log aggregation system inspired by Prometheus.
- [Grafana Tempo](https://grafana.com/oss/tempo/) - Grafana Tempo is an open source, easy-to-use, and high-scale distributed tracing backend.
- [Graylog](https://www.graylog.org/) - Graylog is a fully integrated open source log management platform for collecting, indexing, and analyzing both structured and unstructured data.
- [Healthchecks](https://github.com/healthchecks/healthchecks) - Healthchecks is a cron job monitoring service. It listens for HTTP requests and email messages ("pings") from your cron jobs and scheduled tasks.
- [Icinga](https://icinga.com/) - Icinga is a monitoring system which checks the availability of your network resources, notifies users of outages, and generates performance data for reporting.
- [InfluxData](https://www.influxdata.com/) - InfluxData is driven to create the most powerful platform for developing time series applications.
- [Jaeger](https://www.jaegertracing.io/) - Jaeger is an open source end-to-end distributed tracing system, originally developed by Uber Technologies and now a CNCF graduated project.
- [Kibana](https://www.elastic.co/products/kibana) - Kibana is a free and open user interface that lets you visualize your Elasticsearch data and navigate the Elastic Stack.
- [Logstash](https://www.elastic.co/products/logstash) - Logstash is a free and open server-side data processing pipeline that ingests data from a multitude of sources, transforms it, and then sends it to your favorite "stash."
- [Nagios](https://www.nagios.org/) - Nagios is an open source monitoring system for computer systems designed to run on Linux and monitor devices running Linux, Windows and Unix operating systems.
- [Netdata](https://www.netdata.cloud/) - Netdata is an open source tool designed to collect real-time metrics, such as CPU usage, disk activity, bandwidth usage, and website visits, and then display them in live, easy-to-interpret charts.
- [New Relic](https://newrelic.com/) - New Relic is a cloud-based observability platform that provides end-to-end monitoring for applications, infrastructure, and logs, with AI-assisted root cause analysis and distributed tracing.
- [OpenTelemetry](https://opentelemetry.io/) - OpenTelemetry is a CNCF project that provides a collection of APIs, SDKs, and tools to instrument, generate, collect, and export telemetry data (metrics, logs, and traces).
- [Prometheus](https://prometheus.io/) - Prometheus is a free software application used for event monitoring and alerting. It is a CNCF graduated project widely used in cloud-native environments.
- [Sensu](https://sensu.io/) - Sensu is an open source infrastructure and application monitoring solution that monitors servers, services, and application health, and sends alerts and notifications with third-party integration.
- [Sentry](https://sentry.io/welcome/) - Sentry is open-source error tracking that helps developers monitor and fix crashes in real time.
- [SonarQube](https://www.sonarsource.com/products/sonarqube/) - SonarQube is a platform for continuous code quality inspection, providing automated code reviews and static analysis supporting over 35 programming languages.
- [Upright](https://github.com/basecamp/upright) - Upright is an open-source synthetic monitoring system from Basecamp that runs health check probes from multiple geographic sites and reports metrics via Prometheus.
- [Zabbix](https://www.zabbix.com/) - Zabbix is an open source monitoring software tool for diverse IT components, including networks, servers, virtual machines (VMs) and cloud services.

---

## Operating Systems

- [Alpine Linux](https://www.alpinelinux.org/) - Alpine Linux is a security-oriented, lightweight Linux distribution based on musl libc and busybox, widely used as a base for Docker container images.
- [Bottlerocket](https://bottlerocket.dev/) - Bottlerocket is a free and open-source Linux-based OS from AWS, purpose-built to host containers, with an emphasis on security and minimal attack surface.
- [CentOS Stream](https://www.centos.org/) - CentOS Stream is a continuously-delivered distro that tracks just ahead of Red Hat Enterprise Linux (RHEL) development.
- [Fedora CoreOS](https://fedoraproject.org/coreos/) - Fedora CoreOS is a Fedora Edition built specifically for running containerized workloads securely and at scale (successor to CoreOS Container Linux).
- [Flatcar Container Linux](https://www.flatcar.org/) - Flatcar Container Linux is a community-driven, immutable Linux distribution designed for running containers at scale.
- [Photon OS](https://github.com/vmware/photon) - Photon OS™ is an open source Linux container host optimized for cloud-native applications, cloud platforms, and VMware infrastructure.
- [Talos Linux](https://www.talos.dev/) - Talos Linux is a modern OS designed specifically for Kubernetes, managed entirely via an API with no SSH or console access, providing enhanced security.
- [Ubuntu](https://ubuntu.com/) - Ubuntu is the modern, open source operating system on Linux for the enterprise server, desktop, cloud, and IoT.

---

## Programming Languages

- [Go](https://golang.org/) - Go (GoLang) is a robust system-level language used for programming across large-scale network servers and big distributed systems. Many modern DevOps tools (Kubernetes, Terraform, Docker) are written in Go.
- [Python](https://www.python.org/) - Python is commonly used for developing websites and software, task automation, data analysis, and data visualization. It is widely used in DevOps automation and scripting.
- [Ruby](https://www.ruby-lang.org/) - Ruby is most used for building web applications and is used in DevOps tools like Chef and Capistrano.
- [Rust](https://www.rust-lang.org/) - Rust is a systems programming language focused on safety, speed, and concurrency. It is increasingly used for building high-performance DevOps tooling and infrastructure components.
- [TypeScript / JavaScript (Node.js)](https://nodejs.org/) - Node.js and TypeScript are used extensively in DevOps tooling, including Pulumi (IaC), CDK for Terraform, and AWS CDK, allowing developers to define infrastructure using familiar web programming languages.

---

## Security & Compliance (DevSecOps)

DevSecOps integrates security practices throughout the DevOps lifecycle.

- [Aqua Security](https://www.aquasec.com/) - Aqua Security is a cloud-native security platform that secures containers, serverless functions, and cloud VMs across the entire development lifecycle.
- [Checkov](https://www.checkov.io/) - Checkov is a static code analysis tool for scanning IaC configurations (Terraform, CloudFormation, Kubernetes, Helm) for security and compliance misconfigurations.
- [Falco](https://falco.org/) - Falco is an open source cloud-native runtime security tool from the CNCF that detects unexpected behavior in containers and Kubernetes environments.
- [HashiCorp Vault](https://www.vaultproject.io/) - Vault is a tool for securely accessing secrets, managing encryption keys, and controlling access to sensitive data. Now owned by IBM.
- [Infisical](https://infisical.com/) - Infisical is an open source secrets management platform that centralizes secrets across your apps and infrastructure, supporting rotation, access control, and audit logs.
- [Snyk](https://snyk.io/) - Snyk is a developer security platform that integrates with IDEs, pipelines, and registries to find and fix vulnerabilities in code, open source libraries, containers, and IaC.
- [Trivy](https://trivy.dev/) - Trivy is an open source all-in-one security scanner from Aqua Security that finds vulnerabilities and misconfigurations in containers, filesystems, Git repositories, and IaC.
- [Wiz](https://www.wiz.io/) - Wiz is an agentless cloud security platform that scans entire cloud environments for risks including vulnerabilities, misconfigurations, secrets exposure, and overprivileged identities.

---

## Service Mesh & Networking

- [Cilium](https://cilium.io/) - Cilium is a CNCF graduated project that provides eBPF-based networking, security, and observability for Kubernetes environments, replacing traditional iptables-based networking.
- [Istio](https://istio.io/) - Istio is an open source service mesh that layers transparently onto existing distributed applications, providing traffic management, telemetry, and security policy enforcement.
- [Kuma](https://kuma.io/) - Kuma is a CNCF sandbox universal service mesh built on Envoy, supporting both Kubernetes and traditional VM deployments.
- [Linkerd](https://linkerd.io/) - Linkerd is a CNCF graduated ultra-lightweight service mesh for Kubernetes, providing observability, reliability, and security without requiring code changes.
- [Tailscale](https://tailscale.com/) - Tailscale is a zero-config VPN built on WireGuard that makes encrypted networking simple, widely adopted for secure DevOps tooling access and zero-trust networking.

---

## Source Control Management

- [Bitbucket](https://bitbucket.org/product/) - Bitbucket Cloud is a Git-based code hosting and collaboration tool built for teams, with best-in-class Jira and Trello integrations.
- [Forgejo](https://forgejo.org/) - Forgejo is a self-hosted, lightweight code hosting solution and a community-driven fork of Gitea, with a focus on privacy, federation, and freedom.
- [Gitea](https://gitea.io/) - Gitea is a community managed lightweight code hosting solution written in Go.
- [GitHub](https://github.com/) - GitHub is a Git repository hosting service with a rich web-based graphical interface, Actions for CI/CD, Codespaces for cloud development, and Copilot for AI-assisted coding.
- [GitLab](https://gitlab.com/) - GitLab is a complete DevOps platform delivered as a single application, providing source control, CI/CD, security scanning, issue tracking, and wiki documentation.
- [Gogs](https://gogs.io/) - Gogs is a lightweight, self-hosted Git service written in Go, designed to be simple to set up and operate.
- [Perforce Helix Core](https://www.perforce.com/products/helix-core) - Perforce Helix Core is an enterprise version control system designed for large binary assets and massive codebases, widely used in game development and hardware engineering.

---

*Last updated: June 2026*
