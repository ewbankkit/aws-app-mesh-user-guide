# Service Meshes<a name="meshes"></a>

A service mesh is a logical boundary for network traffic between the services that reside within it\. After you create your service mesh, you can create virtual services, virtual nodes, virtual routers, and routes to distribute traffic between the applications in your mesh\.

## Creating a Service Mesh<a name="create-mesh"></a>

To create a service mesh using the AWS Management Console, complete the following steps\. To create a service mesh using the AWS CLI version 1\.16\.266 or higher, see the example in the AWS CLI reference for the [create\-mesh](https://docs.aws.amazon.com/cli/latest/reference/appmesh/create-mesh.html) command\.

1. Open the App Mesh console at [https://console\.aws\.amazon\.com/appmesh/](https://console.aws.amazon.com/appmesh/)\.

1. Choose **Create mesh**\.

1. For **Mesh name**, specify a name for your service mesh\.

1. Choose **Create mesh** to finish\.