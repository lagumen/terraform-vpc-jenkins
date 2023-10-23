# Terraform boiler template to create VPC across two separate AWS AZ's including and not limited to the carving of related subnets for private, public and database namespaces.

_Introducing a Terraform Boilerplate for Cross-Availability Zone VPC Creation:_

I have crafted a simple straightforward Terraform boilerplate template designed for the creation of a Virtual Private Cloud (VPC) that spans two distinct Availability Zones (AZs) within the Amazon Web Services (AWS) ecosystem.

This comprehensive template encompasses the provisioning of subnets, catering to a variety of use cases, including private, public, and database namespaces.

I have leverage the convenience of publicly available modules from the AWS Terraform registry. These modules simplify the process of resource creation in the AWS environment, providing an efficient and streamlined approach to infrastructure deployment.

I also have  strategically positioned this VPC within a dedicated development domain namespace. The private subnet created for the database domain ensures that the database namespace serves as an isolated and controlled environment, tailored to meet the specific needs and requirements of the development phase. If a given use case allows for it, we can simply extend the manifest by including a few lines that define boolean arguments to enable publicaccess to the database. 

