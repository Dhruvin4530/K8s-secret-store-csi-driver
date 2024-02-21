# AWS Secrets Manager Secrets in Kubernetes with Secrets Store CSI Driver

Using AWS Secrets Manager, you can more securely retrieve secrets from Secrets Manager for use in your Kubernetes pods. With the launch of AWS Secrets Manager and Configuration Provider (ASCP), you have a simple-to-use plugin for the industry-standard Kubernetes Secrets Store and Container Storage Interface (CSI) driver, used for providing secrets to applications that operate on Amazon EKS.

With the use of the Secrets Store CSI driver, you can mount secrets from a Secret Manager into a pod. You can securely store and manage your secrets in Secrets Manager, and retrieve them through your applications that are running on Kubernetes, without the need to write custom code.

