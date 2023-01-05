# INCLUSION APP

To deploy this demo app you need to have VMware Tanzu Application Platform with full profile installed.
VMware Tanzu Application Platform is a modular, application-aware platform that provides a rich set of developer tooling and a prepaved path to production to build and deploy software quickly and securely on any compliant public cloud or on-premises Kubernetes cluster.

The first release of this application stores sensors data in an in-memory database and displays the datas. When you stop the app you will lost the datas as it is not stateful and data are ephemeral.

The final release of this application stores data in a postgres database and can display a collection of emojis, as data are persistent.
