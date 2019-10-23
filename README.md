# spring-boot-app
simple spring boot app

# How to run this app on your openshift cluster
If you have a single-node OpenShift cluster, such as Minishift or the Red Hat Container Development Kit or any openshift cluster running, installed and running, you can also deploy your booster there. A single-node OpenShift cluster provides you with access to a cloud environment that is similar to a production environment.

To deploy your booster to a running single-node OpenShift cluster:

$ oc login -u <username> -p <password>

$ oc new-project <Any Project Name>

$ mvn clean fabric8:deploy -Popenshift
