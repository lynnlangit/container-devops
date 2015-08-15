# container-devops

#How Containers are Disrupting Devops
>Containers are disrupting DevOps by automating software delivery into easily manageable segments. The DevOps   is an autonomous, recurring process, comprised of continuous development, integration, and deployment. We asked ourselves, “How are containers redefining how DevOps is handled and what vendors and products are leading the change?”


##Containers Make Environments Consistent
>Containers provide a common set of building blocks that can be reused in any stage of development to recreate identical environments for development, testing, staging, and production. Containers extend the idea of write once; deploy anywhere, to an infrastructure abstraction that application developers can easily consume and operations professionals can predictably manage.

##Containers Make Tooling Consistent
>Containers provide a disposable, reusable unit of tooling that can execute a segment of a delivery pipeline. Now, critical code quality, analysis, build, and test functions can be packaged as containers and consistently reused within developer workspaces, continuous integration systems, and release management tools. Service injection into containers allows developers to code more productively and tooling vendors to provide value in every phase of the pipeline.

##Container Infrastructure

**Primary**
* Amazon AWS 
  * [EC2 Container Service](http://aws.amazon.com/ecs/) (Docker extension tools)
* Apache 
  * [Mesos](http://mesos.apache.org/) (distributed systems and container kernel)
  * [Zookeeper](https://zookeeper.apache.org) (centralizes container configurations)
* Docker 
  * [Compose](https://docs.docker.com/compose/) (define and running multi-container applications)
  * [Machine](https://docs.docker.com/machine/) (automated Docker provisioning)
  * [Swarm](https://docs.docker.com/swarm/) (native clustering for Docker)
* Google GCP 
  * [Compute Engine](https://cloud.google.com/compute/) (PaaS with container managed service)
  * [Kubernetes](http://kubernetes.io/) (orchestration of services running pods of containers)
* Microsoft Azure
  * [Container Apps](http://azure.microsoft.com/blog/2015/06/23/container-apps-now-available-in-the-azure-marketplace/) (PaaS with container-managed services)
* Red Hat 
  * [Atomic](http://www.projectatomic.io/) (lightweight immutable platform for running containers)
  * [OpenShift](https://www.openshift.com/) (hybrid PaaS based on Docker)
* VMware [Photon](https://vmware.github.io/photon/) (lightweight Linux host for containers)

**Secondary**
* ActiveState 
 * [Stackato](http://www.activestate.com/stackato) (agile PaaS platform optimized for containers)
* Alpine 
 * [Linux](http://www.alpinelinux.org) (lightweight operating system container-optimized)
* CenturyLink 
  * [Cloud] (https://www.ctl.io/) (cloud management service with container support)
* Ceph
  * [Ceph](http://ceph.com/) (distributed block storage for Docker)
* ClusterHQ 
 * [Flocker](https://clusterhq.com/2015/06/17/flocker-1-0/) (open source container data volume manager)
* CoreOS 
  * [Tectonic](https://tectonic.com/) (kubernetes cluster for Docker)
  * [flannel](https://coreos.com/flannel/docs/latest/flannel-config.html) (cross-container communication)
* Datawise.io 
 * [Project 6](http://www.datawise.io/project-6.html) (deploy and manage Docker 
containers across clusters)
* EngineYard [Deis](http://deis.io/overview/) (open source PaaS for Docker)
* Joyent [Triton](https://www.joyent.com/) (elastic container infrastructure)
* Kontena [Kontena](http://www.kontena.io/) (application containers for masses)
* HashiCorp 
  * [Packer](https://www.packer.io/) (image construction automation)
  * [Consul](https://www.consul.io/) (finds and configure infrastructure services)
* IBM Cloud
  * [Bluemix](https://console.ng.bluemix.net/) (hybrid PaaS based upon CloudFoundry and Docker)
* Jelastic [Jelastic](https://jelastic.com/docker/) (multi-container orchestration platform)
* Mesosphere [DCOS] (https://mesosphere.com/product/) (data center OS works with Docker)
* Nirmata [Nirmata] (http://nirmata.com/tag/docker/) (application deployment and operations with Docker)
* OpenStack [Nova](https://wiki.openstack.org/wiki/Docker) (launches containers on a massive scale)
* Pertino [Pertino](http://pertino.com/pertino-simplifies-networking-of-docker-containers-across-any-cloud-anywhere) (builds container-level VPC networks)
* Portworx 
 * [PWX](http://portworx.com/products/) (scale out block storage for Docker)
* Rackspace 
 * [Managed Cloud](http://www.rackspace.com/cloud) (management software)
* RancherLabs 
  * [Rancher](http://rancher.com/rancher/) (infrastructure platform for Docker)
  * [RancherOS](http://rancher.com/rancher-os/) (Linux distribution that runs OS as Docker containers) 
* Weave 
 * [Weave](http://weave.in/) (creates a network of Docker containers)

----------------------------------------------------------------------

##10 Step DevOps Pipeline:
1. Code & Check-In
2. Check-Out & Build Code
3. Unit Test & Quality Control
4. Package, Version & Archive
5. Integration Test
6. Deploy-to-Test Environment
7. Deploy-to-Pre-Production
8. Acceptance Test
9. Deploy-to-Production
10. Management & Monitoring

-----------------------------------------------------------------------
##Continuous Delivery has three categories:
1. Continuous Development
2. Continuous Integration
3. Continuous Deployment

----------------------------------------------------------------------
###Continuous Development (IDE + Src Code)

####Developer Workspace
* [Codenvy] (https://codenvy.com/) (RESTful workspaces built with Docker containers)
* [Codefresh] (http://codefresh.io/) (NodeJS workspaces built with Docker)
* Eclipse [Che] (http://www.eclipse.org/che/) (hosted workspaces using containers for microservices)
* JetBrains [IntelliJ IDEA](https://www.jetbrains.com/idea/) (manages Docker containers from IDE)
* [Nitrous](https://pro.nitrous.io/?l=1) (Docker containers as workspaces)
* Progrium [Envy](https://github.com/progrium/envy) (lightweight developer environments)
* [Vagrant](http://docs.vagrantup.com/v2/provisioning/docker.html) (Docker provisioner)
* VMware [AppCatalyst](http://blogs.vmware.com/cloudnative/vmware-appcatalyst) (desktop hypervisor optimized for containers)

####Source Code Management
* GitHub
* AWS
* GCP

###Continuous Integration (CI, Code Analysis, Testing Frameworks, Build Automation)
####Continuous Integration
* [Drone.io](http://blog.drone.io/2014/2/5/open-source-ci-docker.html) (open source continuous integration built on Docker)
* [Electric Cloud](http://electric-cloud.com/plugins/directory/p/docker/) (plug-in to invoke containers while building)
* XebiaLabs [Overcast](https://github.com/xebialabs/overcast) (Docker for integration testing with other services)
* CloudBees [Jenkins CI](https://www.cloudbees.com/jenkins/about/code-quality-analysis) (build slaves runnable within  containers)
* [CircleCi](https://circleci.com/docs/docker) (supports Docker-based dev, test and deploy workflow)
* Codeship [ParallelCI](https://codeship.com/features/parallelci) (parallel testing with containers)
* [Shippable](https://app.shippable.com/) (automated DevOps with Docker)
* [Wercker](http://wercker.com/) (containerized build pipeline)

####Code Quality Analysis
* [Code Climate](https://codeclimate.com/) (static analysis with containers)
* [Screener](https://screener.io/) (screens code before and after being Dockerized)
* [SonarQube](http://www.sonarqube.org/) (code quality with containers)

####Packaging and Build Automation
* Atlassian [Bamboo](https://www.atlassian.com/software/bamboo)(uses Docker containers to create build agents)
* [Bitnami](https://bitnami.com/) (image cloud hosting)
* [Gradle](https://gradle.org) (build management through Docker)

####Testing Frameworks
* [Salt](http://docs.saltstack.com/en/latest/ref/states/all/salt.states.dockerio.html) (allows unit testing within container)
* [SeleniumEnv](https://github.com/Codeception/SeleniumEnv) (can be run through Docker instead of installed)
* [PhantomJsEnv](https://github.com/Codeception/PhantomJsEnv) (can be run through Docker instead of installed)
* [RoboCI](https://github.com/Codegyre/RoboCI) (aimed to run Travis CI builds locally inside Docker containers)

###Continuous Deployment (Image Registry, Release Automation, Operations Tools)
####Artifact and Image Registry
* Docker 
  * [Hub](https://hub.docker.com/) (hosted registry service)
  * [Trusted Registry](https://docs.docker.com/docker-trusted-registry/) (private dedicated image registry)
* GCP
 * [Google Container Registry] (https://cloud.google.com/container-registry/) (secure Docker image storage)

* JFrog [Artifactory](http://www.jfrog.com/confluence/display/RTF/Docker+Repositories) (doubles as Docker and artifact registry)
* [Quay.io](https://quay.io/plans/) (secure hosting for Docker registries)
* [Tutum Registry] (https://support.tutum.co/support/solutions/articles/5000012183-using-tutum-s-private-Docker-image-registry) (private Docker registry)

####Release Automation
* Amazon [OpsWorks](http://aws.amazon.com/opsworks/) (application management for container & VM infrastructure)
* [Ansible](http://www.ansible.com/docker) (playbooks will generate consistent app in containers & VMs)
* [Chef](https://www.chef.io/solutions/containers/) (container management, provisioning and automation)
* PuppetLabs [Puppet Forge](https://forge.puppetlabs.com/tags/docker) (Docker management)
* [Salt](http://docs.saltstack.com/en/latest/ref/states/all/salt.states.dockerio.html) (container management, provisioning and automation)

####Operations Tools
* [AppDynamics](http://community.appdynamics.com/t5/eXchange-Community-AppDynamics/Docker-Monitoring-Extension/idi-p/14749) (extension for Docker monitoring)
* CenturyLink Labs [Panamax] (http://panamax.io/) (tools to visualize & manage containers)
* [New Relic](https://blog.newrelic.com/2015/05/06/docker-support-2/) (distributed container monitoring and analytics)
* [Sysdig Cloud] (https://sysdig.com/distributed-container-monitoring-sysdig-cloud-revolution/) (distributed container monitoring)
* [SignalFx](http://blog.signalfx.com/signalfx-is-proud-to-join-the-docker-ecosystem-technology-partner-program) (streaming analytics of Docker apps)








