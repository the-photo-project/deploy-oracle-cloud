# Deployment to Oracle Cloud

This repository contains some scripts and things to deploy our student learning application to Oracle Cloud.

We chose Oracle Cloud over other options like AWS, Azure, GCP, etc, because:

* Their **Always Free** tier is quite generous in comparison to the other cloud providers, for more details see here: https://docs.oracle.com/en-us/iaas/Content/FreeTier/resourceref.htm
* There are an additional 4 OCPU and 24GB on the ARM-based A1 shapes.
* There has been a recent expansion in the **Always Free** resources, some details are here: https://blogs.oracle.com/cloud-infrastructure/oracle-builds-out-their-portfolio-of-oci-always-free-services -- in particular there are fast NoSQL database options available.
* More details about the **Always Free** resources from Oracle are here: https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm

It's important to note that **Always Free** compute resources on Oracle Cloud must be located in your home region. So you should select your home region correctly when creating your Oracle Cloud account.
