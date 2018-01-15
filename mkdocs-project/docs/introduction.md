# Learn GCP/ Introduction #

There is often a need to implement computing services such as file storage, databases, websites,
and analysis/modeling tools.
A basic decision is whether to buy equipment for on-site installation, or use cloud-hosted services.
Cloud platform features are increasing and costs are decreasing, which makes cloud services attractive.
Many government entities are now using such services to outsource information technology (IT) services,
thereby reducing the need for staff and on-site infrastructure.

The Google Cloud Platform (GCP) is one such cloud solution and is discussed in this documentation.

The remainder of this page discusses the following:

* [Cloud Platform Services Overview](#cloud-platform-services-overview)
* [Alternatives to GCP](#alternatives-to-gcp)
* [Getting Started with GCP](#getting-started-with-gcp)

-----------

## Cloud Platform Services Overview ##

Cloud platforms provide many services to support all of the tasks necessary to implement business solutions.
Important services are summarized below.

### User Management ###

User management involves defining users, roles, and permissions.
For example, a general account may be set up with administrative privileges to manage an organizations cloud resources.
Individual users are set up to allow staff to perform their work.
Each user can be granted roles and permissions, for example to be able to read/write files in cloud storage.

The information related to such configuration can become complex.
GCP therefore provides [Cloud Identify & Access Management](https://cloud.google.com/iam/) tools,
which is accessible through the GCP Console.

The level of access to cloud services will determine whether a user has access to IAM.
In many cases, users and automated processes will simply operate within the environment and components
that have been made available.

* See [Accounts and IAM](accounts-iam).

### Storage ###

Cloud storage is provided via internet-addressable "buckets", each of which contain folders and files.
Files from a local computer can be uploaded and downloaded using the `gcloud` software.
Buckets can be mapped to internet domain addresses to provide static websites.

* See [Choosing a Storage Option](https://cloud.google.com/storage-options/)
* [Storage](storage).

### Computing (Virtual Machines) ###

Computing resources can be made available via various services including providing virtual machines.
Although Microsoft servers may be used, Linux is typically less expensive and provide other functional benefits.
Direct access to a virtual machine is provided though `ssh`, for example to install and configure software.

* See [Google Compute Engine Documentation](https://cloud.google.com/compute/docs/)
* [Virtual Machines](vm)

### Databases ###

Various database services can be enabled as needed.

* See [Choosing a Storage Option](https://cloud.google.com/storage-options/)

### Websites ###

Websites can be hosted in various ways.

* See [Serving Websites](https://cloud.google.com/solutions/web-serving-overview)
* [Websites](website)

## Alternatives to GCP ##

Google Cloud Platform is provided by Google.
The choice of a platform may depend on whether an organization has settled on one platform.
For example, Google and Microsoft provide integrated applications such as email and file storage.
It is also possible to use services from multiple platforms,
for example use Amazon Web Services to supplement the services of other vendors.
Major platform solution alternatives to GCP include:

* [Amazon Web Services](https://aws.amazon.com/)
* [Microsoft Azure](https://azure.microsoft.com/en-us/)

## Getting Started with GCP ##

See the next sections in this documentation for information about setting up accounts
and getting started with GCP.
