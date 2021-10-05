# Categories of Issues

The categories of the issues are as follows:

* Authentication Issue
  
  Any breakage in the following:

  |  |   |
  |---|---|
  | [KIAM v4.0+](https://github.com/uswitch/kiam)|   |
  | [IRSA](https://docs.aws.amazon.com/eks/latest/userguide/iam-roles-for-service-accounts.html)|   |
  | [Kubernetes Secrets](https://github.com/cert-manager/aws-privateca-issuer/blob/master/config/samples/secret.yaml)|    |

* Supported Workflow Broken

  * [Setting up end-to-end TLS encryption on Amazon EKS with the new AWS Load Balancer Controller](https://aws.amazon.com/blogs/containers/setting-up-end-to-end-tls-encryption-on-amazon-eks-with-the-new-aws-load-balancer-controller/)
  * [TLS-enabled Kubernetes clusters with ACM Private CA and Amazon EKS](https://aws.amazon.com/blogs/security/tls-enabled-kubernetes-clusters-with-acm-private-ca-and-amazon-eks-2/)
  * Cross Account CA sharing with supported Cross Account templates
  * Issuing RSA and EC Certificates

* Build Issues



* Broken Testing Infrastructure

  * Breakage in the automatically launced tests while a PR is created
  
  * Breakage in running tests locally

  Please verify that any changes you have made isn't the reason for the break


* Incorrect Documentation

  Any documentation related issues, including incorrect information, typos, broken links etc.

* Other

    Any other issue which does not fit in the above categories.
