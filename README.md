# m2-product-attribute-acl

_Intention of the feature_
- to lock specific attributes from editing specific values of products
- to set permission per product attribute for multiple roles differently
- to set two permission levels per single attribute per role entity
- to grant/ revoke permission to show product attribute values
- (in dependence of previous) to grant/ revoke permission to edit product attribute value
- to define a permission level by default, but you can deviate from that in specific case

_use cases_
- Magento Admin panel user isn't authorized to edit specific product data, because the data sovereignty needs to be assigned to the previous leading data supplying system (e.g. ERP)
- A department, an user (by role) isn't responsible/ authorized to edit specific product data (to increase data quality)
- A department, an user (by role) shouldn't see specific product data values, so they can focus on their real task. (to increase usability)
