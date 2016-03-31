### Add Alternate Login

Set-AdfsClaimsProviderTrust -TargetIdentifier "AD AUTHORITY" -AlternateLoginID mail -LookupForests example.local

### ADFS meta data link
https://{server}/FederationMetadata/2007-06/FederationMetadata.xml

### vcLoud Org meta data link
https://{vcloud server}/cloud/org/{orgname}/saml/metadata/alias/vcd