# Supported Regions<a name="acm-regions"></a>

Visit [AWS Regions and Endpoints](https://docs.aws.amazon.com/general/latest/gr/rande.html#acm_region) in the *AWS General Reference* or the [AWS Region Table](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/) to see the regional availability for ACM\. 

Like most AWS resources, certificates in ACM are regional resources\. To use a certificate with Elastic Load Balancing for the same fully qualified domain name \(FQDN\) or set of FQDNs in more than one AWS region, you must request or import a certificate for each region\. For certificates provided by ACM, this means you must revalidate each domain name in the certificate for each region\. You cannot copy a certificate between regions\. 

To use an ACM Certificate with Amazon CloudFront, you must request or import the certificate in the US East \(N\. Virginia\) region\. ACM Certificates in this region that are associated with a CloudFront distribution are distributed to all the geographic locations configured for that distribution\. 