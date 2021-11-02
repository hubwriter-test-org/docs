
If your {% data variables.product.prodname_actions %} workflows need to access resources from a cloud provider that supports OpenID Connect (OIDC), you can configure your workflows to authenticate directly to the cloud provider. This will let you stop storing these credentials as long-lived secrets and provide other security benefits. For more information, see "[About security hardening with OpenID Connect](/actions/deployment/security-hardening-your-deployments/about-security-hardening-with-openid-connect)"