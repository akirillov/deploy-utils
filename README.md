Ansible Deployment Roles
============

### Set of roles for deployment and configuration routines automation with Ansible.

For now next roles are present:
* __common__ includes some basic deb dependencies and locale setup for bootstrapping target machine
* __mesos__ provides configurable HA Mesos cluster setup (see [mesos-cluster.yml](mesos-cluster.yml) for reference)
* __oracle-java__ automatically sets up Oracle JDK with no need for manually approve the licence
* __sbt__ role downloads and sets up SBT available from public Typesafe repository
* __scala__ role for Scala setup
* __spark-r__ sets up R language environment and builds [SparkR](http://amplab-extras.github.io/SparkR-pkg/) integration for Apache Spark
* __zookeeper__ installation of zookeeper cluster (TODO: provide example and README)

Coming soon: examples of each role usage