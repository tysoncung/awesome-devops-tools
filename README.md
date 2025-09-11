# Awesome DevOps Tools 🚀 [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A comprehensive collection of DevOps tools for modern software development and operations

This repository contains a curated list of DevOps tools across the entire software delivery lifecycle. From planning to monitoring, we've got you covered with both open-source and commercial solutions.

## 📑 Table of Contents

- [📋 Planning & Collaboration](#planning--collaboration)
- [🔧 Source Code Management](#source-code-management)
- [🏗️ CI/CD](#cicd)
  - [Continuous Integration](#continuous-integration)
  - [Continuous Deployment](#continuous-deployment)
  - [GitOps](#gitops)
- [📦 Build Tools](#build-tools)
- [🐳 Containerization](#containerization)
  - [Container Platforms](#container-platforms)
  - [Container Registries](#container-registries)
  - [Container Security](#container-security)
- [🎯 Orchestration](#orchestration)
- [☁️ Cloud Platforms](#cloud-platforms)
  - [Public Cloud](#public-cloud)
  - [Private Cloud](#private-cloud)
  - [Multi-Cloud Management](#multi-cloud-management)
- [🏗️ Infrastructure as Code](#infrastructure-as-code)
- [📊 Configuration Management](#configuration-management)
- [📈 Monitoring & Observability](#monitoring--observability)
  - [Metrics & Monitoring](#metrics--monitoring)
  - [Log Management](#log-management)
  - [APM & Tracing](#apm--tracing)
  - [Status Pages](#status-pages)
- [🔒 Security](#security)
  - [Security Scanning](#security-scanning)
  - [Secrets Management](#secrets-management)
  - [Policy as Code](#policy-as-code)
- [🧪 Testing](#testing)
- [📦 Artifact Management](#artifact-management)
- [🌐 Service Mesh](#service-mesh)
- [💾 Database DevOps](#database-devops)
- [🤖 AIOps & Automation](#aiops--automation)
- [📚 Documentation](#documentation)
- [🎯 Feature Flags](#feature-flags)
- [💬 ChatOps](#chatops)
- [🔧 Development Tools](#development-tools)

---

## 📋 Planning & Collaboration

### Project Management
- **[Jira](https://www.atlassian.com/software/jira)** - Issue tracking and agile project management
- **[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)** - Microsoft's DevOps platform
- **[GitLab](https://gitlab.com)** - Complete DevOps platform
- **[Linear](https://linear.app)** - Modern issue tracking for software teams
- **[Shortcut](https://shortcut.com)** - Project management for software teams
- **[Monday.dev](https://monday.com/dev)** - Work OS for development teams
- **[Plane](https://plane.so)** - Open-source Jira alternative #opensource

### Collaboration
- **[Slack](https://slack.com)** - Team collaboration hub
- **[Microsoft Teams](https://teams.microsoft.com)** - Chat-based workspace
- **[Discord](https://discord.com)** - Voice, video, and text communication
- **[Mattermost](https://mattermost.com)** - Open-source team collaboration #opensource
- **[Rocket.Chat](https://rocket.chat)** - Open-source team communication #opensource
- **[Zulip](https://zulip.com)** - Open-source team chat #opensource

---

## 🔧 Source Code Management

### Version Control Systems
- **[Git](https://git-scm.com)** - Distributed version control system #opensource
- **[GitHub](https://github.com)** - Git hosting and collaboration
- **[GitLab](https://gitlab.com)** - Git repository management
- **[Bitbucket](https://bitbucket.org)** - Git and Mercurial hosting
- **[Gitea](https://gitea.io)** - Lightweight Git hosting #opensource
- **[Gogs](https://gogs.io)** - Painless self-hosted Git service #opensource
- **[AWS CodeCommit](https://aws.amazon.com/codecommit/)** - Managed Git repositories
- **[Perforce](https://www.perforce.com)** - Enterprise version control

### Code Review
- **[Gerrit](https://www.gerritcodereview.com)** - Web-based code review #opensource
- **[Phabricator](https://www.phacility.com/phabricator/)** - Code review and repository hosting #opensource
- **[Review Board](https://www.reviewboard.org)** - Web-based code review #opensource
- **[Crucible](https://www.atlassian.com/software/crucible)** - Code review by Atlassian

---

## 🏗️ CI/CD

### Continuous Integration

#### Self-Hosted
- **[Jenkins](https://jenkins.io)** - Leading open-source automation server #opensource
- **[GitLab CI](https://docs.gitlab.com/ee/ci/)** - Built-in CI/CD for GitLab #opensource
- **[Drone](https://drone.io)** - Container-native CI/CD #opensource
- **[Tekton](https://tekton.dev)** - Cloud-native CI/CD #opensource
- **[Buildkite](https://buildkite.com)** - Fast, secure, scalable CI/CD
- **[TeamCity](https://www.jetbrains.com/teamcity/)** - CI/CD by JetBrains
- **[Bamboo](https://www.atlassian.com/software/bamboo)** - CI/CD by Atlassian
- **[GoCD](https://www.gocd.org)** - Open-source CI/CD server #opensource
- **[Concourse](https://concourse-ci.org)** - Container-based CI/CD #opensource
- **[Zuul](https://zuul-ci.org)** - Project gating system #opensource

#### Cloud-Based
- **[GitHub Actions](https://github.com/features/actions)** - CI/CD for GitHub
- **[CircleCI](https://circleci.com)** - Continuous integration and delivery
- **[Travis CI](https://travis-ci.com)** - Test and deploy with confidence
- **[Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/)** - Build, test, and deploy
- **[AWS CodeBuild](https://aws.amazon.com/codebuild/)** - Build and test code
- **[Google Cloud Build](https://cloud.google.com/build)** - Build, test, and deploy
- **[Codefresh](https://codefresh.io)** - GitOps automation platform
- **[Semaphore](https://semaphoreci.com)** - Fast CI/CD
- **[Buddy](https://buddy.works)** - CI/CD with instant deployments

### Continuous Deployment

- **[Spinnaker](https://spinnaker.io)** - Multi-cloud continuous delivery #opensource
- **[ArgoCD](https://argoproj.github.io/cd)** - Declarative GitOps CD for Kubernetes #opensource
- **[Flux](https://fluxcd.io)** - GitOps for Kubernetes #opensource
- **[Octopus Deploy](https://octopus.com)** - Deployment automation
- **[AWS CodeDeploy](https://aws.amazon.com/codedeploy/)** - Automated deployments
- **[Harness](https://harness.io)** - Software delivery platform
- **[Humanitec](https://humanitec.com)** - Internal developer platform

### GitOps

- **[ArgoCD](https://argoproj.github.io/cd)** - Declarative GitOps for Kubernetes #opensource
- **[Flux](https://fluxcd.io)** - GitOps toolkit #opensource
- **[Fleet](https://fleet.rancher.io)** - GitOps at scale #opensource
- **[Weave GitOps](https://www.weave.works/product/gitops/)** - Enterprise GitOps
- **[Jenkins X](https://jenkins-x.io)** - Cloud-native CI/CD #opensource

---

## 📦 Build Tools

### Build Automation
- **[Maven](https://maven.apache.org)** - Build automation for Java #opensource
- **[Gradle](https://gradle.org)** - Build automation #opensource
- **[Bazel](https://bazel.build)** - Fast, scalable build system #opensource
- **[Make](https://www.gnu.org/software/make/)** - Build automation tool #opensource
- **[Ant](https://ant.apache.org)** - Java build tool #opensource
- **[npm](https://npmjs.com)** - Package manager for JavaScript #opensource
- **[Yarn](https://yarnpkg.com)** - Fast, reliable JavaScript package manager #opensource
- **[pnpm](https://pnpm.io)** - Fast, disk space efficient package manager #opensource
- **[Poetry](https://python-poetry.org)** - Python dependency management #opensource
- **[Cargo](https://doc.rust-lang.org/cargo/)** - Rust package manager #opensource

### Build Acceleration
- **[Buildkit](https://github.com/moby/buildkit)** - Concurrent, cache-efficient builds #opensource
- **[Earthly](https://earthly.dev)** - Better builds #opensource
- **[Pants](https://www.pantsbuild.org)** - Fast, scalable build system #opensource
- **[Buck](https://buck.build)** - Fast build system #opensource
- **[Nx](https://nx.dev)** - Smart, fast, extensible build system #opensource

---

## 🐳 Containerization

### Container Platforms
- **[Docker](https://docker.com)** - Leading container platform
- **[Podman](https://podman.io)** - Daemonless container engine #opensource
- **[containerd](https://containerd.io)** - Industry-standard container runtime #opensource
- **[CRI-O](https://cri-o.io)** - Lightweight container runtime for Kubernetes #opensource
- **[LXC/LXD](https://linuxcontainers.org)** - Linux containers #opensource
- **[Kata Containers](https://katacontainers.io)** - Secure container runtime #opensource
- **[gVisor](https://gvisor.dev)** - Application kernel for containers #opensource
- **[Firecracker](https://firecracker-microvm.github.io)** - Secure and fast microVMs #opensource

### Container Registries
- **[Docker Hub](https://hub.docker.com)** - Docker's official registry
- **[Amazon ECR](https://aws.amazon.com/ecr/)** - AWS container registry
- **[Google Container Registry](https://cloud.google.com/container-registry)** - GCP registry
- **[Azure Container Registry](https://azure.microsoft.com/en-us/services/container-registry/)** - Azure registry
- **[Harbor](https://goharbor.io)** - Cloud-native registry #opensource
- **[Quay](https://quay.io)** - Container registry by Red Hat
- **[Nexus](https://www.sonatype.com/nexus-repository-sonatype)** - Repository manager
- **[JFrog Artifactory](https://jfrog.com/artifactory/)** - Universal repository
- **[GitLab Container Registry](https://docs.gitlab.com/ee/user/packages/container_registry/)** - Built-in registry

### Container Security
- **[Trivy](https://trivy.dev)** - Security scanner #opensource
- **[Clair](https://github.com/quay/clair)** - Vulnerability scanner #opensource
- **[Anchore](https://anchore.com)** - Container security and compliance
- **[Snyk Container](https://snyk.io/product/container-vulnerability-scanning/)** - Container vulnerability scanning
- **[Twistlock](https://www.paloaltonetworks.com/prisma/cloud)** - Container security platform
- **[Falco](https://falco.org)** - Runtime security #opensource
- **[Sysdig](https://sysdig.com)** - Container security and monitoring

---

## 🎯 Orchestration

### Container Orchestration
- **[Kubernetes](https://kubernetes.io)** - Container orchestration #opensource
- **[OpenShift](https://www.openshift.com)** - Enterprise Kubernetes by Red Hat
- **[Docker Swarm](https://docs.docker.com/engine/swarm/)** - Docker's orchestration
- **[Nomad](https://www.nomadproject.io)** - Simple and flexible orchestrator #opensource
- **[Apache Mesos](https://mesos.apache.org)** - Distributed systems kernel #opensource
- **[DC/OS](https://dcos.io)** - Distributed operating system #opensource
- **[Amazon ECS](https://aws.amazon.com/ecs/)** - AWS container orchestration
- **[Amazon EKS](https://aws.amazon.com/eks/)** - Managed Kubernetes on AWS
- **[Google GKE](https://cloud.google.com/kubernetes-engine)** - Managed Kubernetes on GCP
- **[Azure AKS](https://azure.microsoft.com/en-us/services/kubernetes-service/)** - Managed Kubernetes on Azure

### Kubernetes Management
- **[Rancher](https://rancher.com)** - Kubernetes management platform #opensource
- **[Lens](https://k8slens.dev)** - Kubernetes IDE #opensource
- **[K9s](https://k9scli.io)** - Terminal UI for Kubernetes #opensource
- **[Portainer](https://www.portainer.io)** - Container management UI #opensource
- **[Kubesphere](https://kubesphere.io)** - Distributed Kubernetes platform #opensource
- **[Kops](https://kops.sigs.k8s.io)** - Kubernetes operations #opensource
- **[Kubespray](https://kubespray.io)** - Deploy production-ready Kubernetes #opensource

---

## ☁️ Cloud Platforms

### Public Cloud
- **[Amazon Web Services (AWS)](https://aws.amazon.com)** - Leading cloud platform
- **[Microsoft Azure](https://azure.microsoft.com)** - Microsoft's cloud platform
- **[Google Cloud Platform](https://cloud.google.com)** - Google's cloud platform
- **[IBM Cloud](https://www.ibm.com/cloud)** - IBM's cloud platform
- **[Oracle Cloud](https://www.oracle.com/cloud/)** - Oracle's cloud platform
- **[Alibaba Cloud](https://www.alibabacloud.com)** - Alibaba's cloud platform
- **[DigitalOcean](https://www.digitalocean.com)** - Developer-friendly cloud
- **[Linode](https://www.linode.com)** - Simple cloud infrastructure
- **[Vultr](https://www.vultr.com)** - High-performance cloud
- **[Hetzner Cloud](https://www.hetzner.com/cloud)** - German cloud provider

### Private Cloud
- **[OpenStack](https://www.openstack.org)** - Open-source cloud platform #opensource
- **[CloudStack](https://cloudstack.apache.org)** - Open-source cloud computing #opensource
- **[OpenNebula](https://opennebula.io)** - Simple cloud platform #opensource
- **[VMware vSphere](https://www.vmware.com/products/vsphere.html)** - Enterprise virtualization
- **[Proxmox](https://www.proxmox.com)** - Open-source virtualization #opensource

### Multi-Cloud Management
- **[Terraform Cloud](https://www.terraform.io/cloud)** - Multi-cloud infrastructure automation
- **[Pulumi](https://www.pulumi.com)** - Modern infrastructure as code
- **[Crossplane](https://crossplane.io)** - Cloud-native control plane #opensource
- **[Cloudify](https://cloudify.co)** - Multi-cloud orchestration

---

## 🏗️ Infrastructure as Code

### Provisioning
- **[Terraform](https://www.terraform.io)** - Infrastructure as code #opensource
- **[Pulumi](https://www.pulumi.com)** - Modern infrastructure as code
- **[AWS CloudFormation](https://aws.amazon.com/cloudformation/)** - IaC for AWS
- **[Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/)** - IaC for Azure
- **[Google Cloud Deployment Manager](https://cloud.google.com/deployment-manager)** - IaC for GCP
- **[Crossplane](https://crossplane.io)** - Kubernetes-native IaC #opensource
- **[CDK](https://aws.amazon.com/cdk/)** - Cloud Development Kit
- **[Bicep](https://github.com/Azure/bicep)** - DSL for Azure ARM templates #opensource

### Configuration as Code
- **[Ansible](https://www.ansible.com)** - Automation platform #opensource
- **[Puppet](https://puppet.com)** - Configuration management
- **[Chef](https://www.chef.io)** - Configuration management
- **[SaltStack](https://saltproject.io)** - Configuration management #opensource
- **[CFEngine](https://cfengine.com)** - Configuration management

---

## 📊 Configuration Management

### Application Configuration
- **[Consul](https://www.consul.io)** - Service mesh and configuration #opensource
- **[etcd](https://etcd.io)** - Distributed key-value store #opensource
- **[Apache Zookeeper](https://zookeeper.apache.org)** - Coordination service #opensource
- **[Spring Cloud Config](https://spring.io/projects/spring-cloud-config)** - Distributed configuration #opensource
- **[AWS Systems Manager](https://aws.amazon.com/systems-manager/)** - Parameter store
- **[Azure App Configuration](https://azure.microsoft.com/en-us/services/app-configuration/)** - Configuration service

### Database Schema Management
- **[Liquibase](https://www.liquibase.org)** - Database change management #opensource
- **[Flyway](https://flywaydb.org)** - Database migration #opensource
- **[Alembic](https://alembic.sqlalchemy.org)** - Database migrations for SQLAlchemy #opensource
- **[Atlas](https://atlasgo.io)** - Database schema as code #opensource

---

## 📈 Monitoring & Observability

### Metrics & Monitoring
- **[Prometheus](https://prometheus.io)** - Monitoring and alerting #opensource
- **[Grafana](https://grafana.com)** - Observability platform #opensource
- **[Datadog](https://www.datadoghq.com)** - Monitoring and analytics platform
- **[New Relic](https://newrelic.com)** - Full-stack observability
- **[Dynatrace](https://www.dynatrace.com)** - Software intelligence platform
- **[AppDynamics](https://www.appdynamics.com)** - Application performance monitoring
- **[Zabbix](https://www.zabbix.com)** - Enterprise monitoring #opensource
- **[Nagios](https://www.nagios.org)** - Infrastructure monitoring #opensource
- **[Icinga](https://icinga.com)** - Monitoring solution #opensource
- **[Checkmk](https://checkmk.com)** - IT monitoring #opensource
- **[VictoriaMetrics](https://victoriametrics.com)** - Time series database #opensource
- **[InfluxDB](https://www.influxdata.com)** - Time series database #opensource
- **[TimescaleDB](https://www.timescale.com)** - Time series database #opensource

### Log Management
- **[Elasticsearch](https://www.elastic.co)** - Search and analytics engine #opensource
- **[Splunk](https://www.splunk.com)** - Data platform
- **[Logstash](https://www.elastic.co/logstash)** - Log pipeline #opensource
- **[Fluentd](https://www.fluentd.org)** - Data collector #opensource
- **[Fluent Bit](https://fluentbit.io)** - Fast log processor #opensource
- **[Graylog](https://www.graylog.org)** - Log management #opensource
- **[Loki](https://grafana.com/oss/loki/)** - Log aggregation #opensource
- **[Papertrail](https://www.papertrail.com)** - Cloud-hosted log management
- **[Loggly](https://www.loggly.com)** - Log analysis
- **[Sumo Logic](https://www.sumologic.com)** - Cloud-native log analytics
- **[Vector](https://vector.dev)** - Observability data pipeline #opensource

### APM & Tracing
- **[Jaeger](https://www.jaegertracing.io)** - Distributed tracing #opensource
- **[Zipkin](https://zipkin.io)** - Distributed tracing #opensource
- **[AWS X-Ray](https://aws.amazon.com/xray/)** - Application tracing
- **[Google Cloud Trace](https://cloud.google.com/trace)** - Distributed tracing
- **[Azure Application Insights](https://azure.microsoft.com/en-us/services/monitor/)** - APM for Azure
- **[Apache SkyWalking](https://skywalking.apache.org)** - APM and observability #opensource
- **[Tempo](https://grafana.com/oss/tempo/)** - Distributed tracing backend #opensource
- **[Elastic APM](https://www.elastic.co/apm)** - Application performance monitoring
- **[OpenTelemetry](https://opentelemetry.io)** - Observability framework #opensource
- **[Lightstep](https://lightstep.com)** - Observability platform

### Status Pages
- **[Statuspage](https://www.atlassian.com/software/statuspage)** - Status page by Atlassian
- **[Cachet](https://cachethq.io)** - Open-source status page #opensource
- **[Upptime](https://upptime.js.org)** - GitHub-powered uptime monitor #opensource
- **[Better Uptime](https://betteruptime.com)** - Monitoring and status pages
- **[StatusPal](https://statuspal.io)** - Status page and monitoring
- **[Instatus](https://instatus.com)** - Quick status pages

---

## 🔒 Security

### Security Scanning

#### SAST (Static Application Security Testing)
- **[SonarQube](https://www.sonarqube.org)** - Code quality and security #opensource
- **[Checkmarx](https://checkmarx.com)** - Application security testing
- **[Veracode](https://www.veracode.com)** - Application security platform
- **[Fortify](https://www.microfocus.com/en-us/cyberres/application-security)** - Application security
- **[Semgrep](https://semgrep.dev)** - Static analysis #opensource
- **[CodeQL](https://codeql.github.com)** - Semantic code analysis #opensource
- **[Bandit](https://bandit.readthedocs.io)** - Python security linter #opensource
- **[ESLint](https://eslint.org)** - JavaScript linter #opensource

#### DAST (Dynamic Application Security Testing)
- **[OWASP ZAP](https://www.zaproxy.org)** - Web app security scanner #opensource
- **[Burp Suite](https://portswigger.net/burp)** - Web vulnerability scanner
- **[Acunetix](https://www.acunetix.com)** - Web vulnerability scanner
- **[Netsparker](https://www.netsparker.com)** - Web application security

#### Container & Infrastructure Security
- **[Trivy](https://trivy.dev)** - Comprehensive security scanner #opensource
- **[Grype](https://github.com/anchore/grype)** - Vulnerability scanner #opensource
- **[Syft](https://github.com/anchore/syft)** - SBOM generator #opensource
- **[Terrascan](https://runterrascan.io)** - IaC security scanner #opensource
- **[Checkov](https://www.checkov.io)** - IaC static analysis #opensource
- **[tfsec](https://aquasecurity.github.io/tfsec/)** - Terraform security scanner #opensource
- **[KICS](https://kics.io)** - IaC security scanner #opensource
- **[Kubesec](https://kubesec.io)** - Kubernetes security #opensource

### Secrets Management
- **[HashiCorp Vault](https://www.vaultproject.io)** - Secrets management #opensource
- **[AWS Secrets Manager](https://aws.amazon.com/secrets-manager/)** - AWS secrets management
- **[Azure Key Vault](https://azure.microsoft.com/en-us/services/key-vault/)** - Azure secrets management
- **[Google Secret Manager](https://cloud.google.com/secret-manager)** - GCP secrets management
- **[CyberArk](https://www.cyberark.com)** - Privileged access management
- **[Doppler](https://www.doppler.com)** - Secrets management platform
- **[1Password Secrets](https://1password.com/secrets/)** - Developer secrets management
- **[Infisical](https://infisical.com)** - Open-source secrets management #opensource
- **[Sealed Secrets](https://sealed-secrets.netlify.app)** - Kubernetes secrets #opensource
- **[External Secrets Operator](https://external-secrets.io)** - Kubernetes secrets #opensource

### Policy as Code
- **[Open Policy Agent](https://www.openpolicyagent.org)** - Policy engine #opensource
- **[Falco](https://falco.org)** - Runtime security #opensource
- **[Polaris](https://www.fairwinds.com/polaris)** - Kubernetes policy #opensource
- **[Kyverno](https://kyverno.io)** - Kubernetes native policy #opensource
- **[ValidatingAdmissionPolicy](https://kubernetes.io/docs/reference/access-authn-authz/validating-admission-policy/)** - K8s admission control

---

## 🧪 Testing

### Test Automation
- **[Selenium](https://www.selenium.dev)** - Web browser automation #opensource
- **[Cypress](https://www.cypress.io)** - JavaScript E2E testing #opensource
- **[Playwright](https://playwright.dev)** - Cross-browser testing #opensource
- **[Puppeteer](https://pptr.dev)** - Headless Chrome automation #opensource
- **[TestCafe](https://testcafe.io)** - E2E web testing #opensource
- **[Robot Framework](https://robotframework.org)** - Generic test automation #opensource
- **[Appium](https://appium.io)** - Mobile app automation #opensource
- **[Katalon Studio](https://katalon.com)** - Test automation platform
- **[Postman](https://www.postman.com)** - API testing
- **[Insomnia](https://insomnia.rest)** - API client and testing #opensource
- **[REST Assured](https://rest-assured.io)** - Java API testing #opensource
- **[K6](https://k6.io)** - Load testing #opensource

### Performance Testing
- **[JMeter](https://jmeter.apache.org)** - Load testing #opensource
- **[Gatling](https://gatling.io)** - Load testing #opensource
- **[Locust](https://locust.io)** - Load testing in Python #opensource
- **[K6](https://k6.io)** - Modern load testing #opensource
- **[Artillery](https://artillery.io)** - Load testing toolkit #opensource
- **[BlazeMeter](https://www.blazemeter.com)** - Continuous testing platform
- **[LoadRunner](https://www.microfocus.com/en-us/products/loadrunner-professional/)** - Performance testing

### Chaos Engineering
- **[Chaos Monkey](https://netflix.github.io/chaosmonkey/)** - Resiliency testing #opensource
- **[LitmusChaos](https://litmuschaos.io)** - Cloud-native chaos engineering #opensource
- **[Gremlin](https://www.gremlin.com)** - Chaos engineering platform
- **[Chaos Mesh](https://chaos-mesh.org)** - Chaos engineering for Kubernetes #opensource
- **[Toxiproxy](https://github.com/Shopify/toxiproxy)** - Network condition simulation #opensource

---

## 📦 Artifact Management

### Package Registries
- **[JFrog Artifactory](https://jfrog.com/artifactory/)** - Universal artifact repository
- **[Sonatype Nexus](https://www.sonatype.com/products/nexus-repository)** - Repository manager
- **[GitHub Packages](https://github.com/features/packages)** - Package hosting
- **[GitLab Package Registry](https://docs.gitlab.com/ee/user/packages/)** - Built-in registry
- **[npm Registry](https://www.npmjs.com)** - JavaScript packages
- **[PyPI](https://pypi.org)** - Python packages
- **[Maven Central](https://search.maven.org)** - Java packages
- **[Docker Hub](https://hub.docker.com)** - Container images
- **[Helm Hub](https://artifacthub.io)** - Kubernetes packages
- **[Cloudsmith](https://cloudsmith.com)** - Universal package management

---

## 🌐 Service Mesh

- **[Istio](https://istio.io)** - Connect, secure, control microservices #opensource
- **[Linkerd](https://linkerd.io)** - Ultralight service mesh #opensource
- **[Consul Connect](https://www.consul.io/docs/connect)** - Service mesh by HashiCorp #opensource
- **[AWS App Mesh](https://aws.amazon.com/app-mesh/)** - Application-level networking
- **[Kuma](https://kuma.io)** - Universal service mesh #opensource
- **[Open Service Mesh](https://openservicemesh.io)** - Lightweight service mesh #opensource
- **[Traefik Mesh](https://traefik.io/traefik-mesh/)** - Simple service mesh #opensource
- **[NGINX Service Mesh](https://www.nginx.com/products/nginx-service-mesh/)** - Enterprise service mesh

---

## 💾 Database DevOps

### Database Management
- **[DBeaver](https://dbeaver.io)** - Universal database tool #opensource
- **[DataGrip](https://www.jetbrains.com/datagrip/)** - Database IDE by JetBrains
- **[pgAdmin](https://www.pgadmin.org)** - PostgreSQL management #opensource
- **[phpMyAdmin](https://www.phpmyadmin.net)** - MySQL management #opensource
- **[Adminer](https://www.adminer.org)** - Database management #opensource
- **[TablePlus](https://tableplus.com)** - Modern database management
- **[Beekeeper Studio](https://www.beekeeperstudio.io)** - SQL editor and database manager #opensource

### Database Migration
- **[Flyway](https://flywaydb.org)** - Database migration #opensource
- **[Liquibase](https://www.liquibase.org)** - Database change management #opensource
- **[Alembic](https://alembic.sqlalchemy.org)** - Database migrations #opensource
- **[golang-migrate](https://github.com/golang-migrate/migrate)** - Database migrations #opensource
- **[Prisma Migrate](https://www.prisma.io/migrate)** - Database schema migration
- **[Atlas](https://atlasgo.io)** - Database schema as code #opensource

### Database Monitoring
- **[Percona Monitoring](https://www.percona.com/software/database-tools/percona-monitoring-and-management)** - Database monitoring #opensource
- **[pganalyze](https://pganalyze.com)** - PostgreSQL performance monitoring
- **[VividCortex](https://www.vividcortex.com)** - Database performance monitoring
- **[Datadog Database Monitoring](https://www.datadoghq.com/product/database-monitoring/)** - Database observability

---

## 🤖 AIOps & Automation

### AIOps Platforms
- **[Moogsoft](https://www.moogsoft.com)** - AI-driven observability
- **[BigPanda](https://www.bigpanda.io)** - AIOps platform
- **[PagerDuty](https://www.pagerduty.com)** - Incident response platform
- **[Opsgenie](https://www.atlassian.com/software/opsgenie)** - Incident management
- **[VictorOps](https://www.splunk.com/en_us/products/on-call.html)** - Incident management

### Automation & Orchestration
- **[Ansible Tower](https://www.ansible.com/products/tower)** - Enterprise automation
- **[Rundeck](https://www.rundeck.com)** - Runbook automation #opensource
- **[StackStorm](https://stackstorm.com)** - Event-driven automation #opensource
- **[Apache Airflow](https://airflow.apache.org)** - Workflow orchestration #opensource
- **[Prefect](https://www.prefect.io)** - Workflow orchestration #opensource
- **[Dagster](https://dagster.io)** - Data orchestration #opensource
- **[Temporal](https://temporal.io)** - Workflow orchestration #opensource
- **[Argo Workflows](https://argoproj.github.io/workflows/)** - Kubernetes-native workflows #opensource
- **[n8n](https://n8n.io)** - Workflow automation #opensource
- **[Zapier](https://zapier.com)** - Automation platform

---

## 📚 Documentation

### Documentation Platforms
- **[Confluence](https://www.atlassian.com/software/confluence)** - Team collaboration
- **[ReadTheDocs](https://readthedocs.org)** - Documentation hosting #opensource
- **[GitBook](https://www.gitbook.com)** - Documentation platform
- **[Docusaurus](https://docusaurus.io)** - Documentation websites #opensource
- **[MkDocs](https://www.mkdocs.org)** - Static site generator #opensource
- **[Sphinx](https://www.sphinx-doc.org)** - Documentation generator #opensource
- **[Hugo](https://gohugo.io)** - Static site generator #opensource
- **[Jekyll](https://jekyllrb.com)** - Static site generator #opensource
- **[Backstage](https://backstage.io)** - Developer portal #opensource
- **[Notion](https://www.notion.so)** - All-in-one workspace
- **[Outline](https://www.getoutline.com)** - Knowledge base #opensource

### API Documentation
- **[Swagger/OpenAPI](https://swagger.io)** - API documentation #opensource
- **[Postman](https://www.postman.com)** - API platform
- **[Stoplight](https://stoplight.io)** - API design and documentation
- **[ReadMe](https://readme.com)** - API documentation
- **[Redoc](https://redocly.com)** - API documentation #opensource
- **[Slate](https://slatedocs.github.io/slate/)** - API documentation #opensource

---

## 🎯 Feature Flags

- **[LaunchDarkly](https://launchdarkly.com)** - Feature management platform
- **[Split](https://www.split.io)** - Feature flags and experimentation
- **[Optimizely](https://www.optimizely.com)** - Digital experience platform
- **[Flagsmith](https://flagsmith.com)** - Feature flag service #opensource
- **[Unleash](https://www.getunleash.io)** - Feature toggle service #opensource
- **[Flipt](https://flipt.io)** - Feature flag application #opensource
- **[GrowthBook](https://www.growthbook.io)** - Feature flags and A/B testing #opensource
- **[ConfigCat](https://configcat.com)** - Feature flag service
- **[Flagr](https://checkr.github.io/flagr/)** - Feature flagging #opensource

---

## 💬 ChatOps

### ChatOps Tools
- **[Hubot](https://hubot.github.com)** - Automation bot framework #opensource
- **[Errbot](https://errbot.io)** - Chatbot framework #opensource
- **[StackStorm](https://stackstorm.com)** - Event-driven automation #opensource
- **[Rundeck](https://www.rundeck.com)** - Runbook automation #opensource
- **[Lita](https://www.lita.io)** - Chat bot framework #opensource
- **[Yetibot](https://yetibot.com)** - Chat bot #opensource

### Incident Management
- **[PagerDuty](https://www.pagerduty.com)** - Incident response
- **[Opsgenie](https://www.atlassian.com/software/opsgenie)** - Alert management
- **[VictorOps](https://www.splunk.com/en_us/products/on-call.html)** - On-call management
- **[FireHydrant](https://firehydrant.io)** - Incident management
- **[Incident.io](https://incident.io)** - Incident management platform
- **[Rootly](https://rootly.io)** - Incident management

---

## 🔧 Development Tools

### IDEs & Editors
- **[Visual Studio Code](https://code.visualstudio.com)** - Code editor by Microsoft #opensource
- **[IntelliJ IDEA](https://www.jetbrains.com/idea/)** - Java IDE
- **[Eclipse](https://www.eclipse.org)** - IDE platform #opensource
- **[Vim](https://www.vim.org)** - Text editor #opensource
- **[Neovim](https://neovim.io)** - Hyperextensible Vim-based editor #opensource
- **[Emacs](https://www.gnu.org/software/emacs/)** - Extensible editor #opensource
- **[Sublime Text](https://www.sublimetext.com)** - Text editor
- **[Atom](https://atom.io)** - Hackable text editor #opensource

### API Development
- **[Postman](https://www.postman.com)** - API platform
- **[Insomnia](https://insomnia.rest)** - API client #opensource
- **[Hoppscotch](https://hoppscotch.io)** - API development #opensource
- **[Bruno](https://www.usebruno.com)** - Fast API client #opensource
- **[Thunder Client](https://www.thunderclient.com)** - REST client for VS Code
- **[HTTPie](https://httpie.io)** - API testing client #opensource
- **[REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)** - VS Code extension

### Database Tools
- **[DBeaver](https://dbeaver.io)** - Database tool #opensource
- **[DataGrip](https://www.jetbrains.com/datagrip/)** - Database IDE
- **[TablePlus](https://tableplus.com)** - Database management
- **[Beekeeper Studio](https://www.beekeeperstudio.io)** - SQL editor #opensource
- **[Azure Data Studio](https://azure.microsoft.com/en-us/products/data-studio)** - Data management tool #opensource

---

## 🌟 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to add new tools or improve existing content.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

⭐ If you find this repository helpful, please consider giving it a star!

Last updated: December 2024