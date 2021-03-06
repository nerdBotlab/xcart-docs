---
lang: en
layout: article_with_sidebar
updated_at: '2015-11-13 00:00'
identifier: ref_SZycMdTx
title: Vendor login and first steps
categories:
  - User manual
published: true
order: 100
redirect_from:
  - >-
    /modules/multi-vendor/multi-vendor_vendor_experience/vendor_login_and_first_steps.html
---

From the viewpoint of X-Cart 5 user access levels, a vendor user is an administrator with the role "Vendor". This means that vendors are allowed to log in to the store's back end, but have access only to a limited set of features (This is called a "Vendor area").

After a vendor account has been registered (see {% link "Vendor registration" ref_SkW62BgH %}), the vendor can log in to their personal Vendor area using any user login form in the store. For example, they can use:

   * the regular Sign in/Sign up form for customers, 
   * the URL for administrator users: `https://<your-domain>/<x-cart-5-directory>/admin.php?target=login`
   * the URL for vendors: `https://<your-domain>/<x-cart-5-directory>/admin.php?target=login_vendor`
     (The portion `http://<your-domain>/<x-cart-5-directory>` needs to be replaced with the actual address of your X-Cart 5 store).

After logging in, the vendor will see a page similar to the following:
![xc5_mv_vendor_dashboard.png]({{site.baseurl}}/attachments/ref_SZycMdTx/xc5_mv_vendor_dashboard.png)

Now the vendor can start selling. The steps below will get them started:

1. If a vendor onboarding welcome message has been provided by the storefront operator (similar to the one in the screenshot above, titled "Welcome to our marketplace"), the vendor should read the message and follow the instructions provided therein. 

2. The vendor should check the information in their user profile and see if anything needs to be added or corrected. See {% link "Managing vendor profile information as a vendor" ref_b7PTQMgf %}.

3.  The vendor should populate the catalog with the products they are going to sell. See {% link "Managing the catalog as a vendor" ref_r4mcwiho %} for information on how vendors can add products to the catalog manually. See {% link "Vendor import/export" ref_pa3oqbXz %} for information on how vendors can add products using CSV import.
    Information on the use of product classes and attributes by vendors can be found in the section {% link "Vendor access to product classes and attributes" ref_TvmooKW9 %}.

4.  If the store is set to work in the "_Vendors as separate shops_" {% link "multivendor mode" ref_nFq48dhr %}:
    *  The vendor must specify the address from which their products will be shipped. This address will be used to calculate the cost of delivery of an order from the vendor's warehouse to the buyer. See {% link "Managing vendor profile information as a vendor" ref_b7PTQMgf#company-details %}

    *  The vendor must specify the shipping methods they are going to use. See {% link "Managing shipping methods as a vendor" ref_IvXmtLKI %}.

    {% note info %}
    (In "_Warehouse_" mode, the products of different vendors are shipped from the same warehouse, so the "ship-from" address and shipping methods are the same for all the vendors; the configuration of the "ship-from" address and shipping methods in this case is done by the store administrator.)
    {% endnote %}

5.  If the store is set to work in the "_Vendors as separate shops_" {% link "multivendor mode" ref_nFq48dhr %}, vendors are responsible for the collection of sales tax, and the store uses an automated sales tax calculation solution like AvaTax or TaxJar:

    *  The vendor must check the Financial details of their profile (**My account** > **Financial details**) and ensure that only the US states in which they are going to do business and which pertain to their nexus are listed in the "US tax calculation" settings section. This is needed to ensure that no tax calculation requests are sent to AvaTax/TaxJar if the user creating an order comes from a state which does not belong to the vendor's nexus.

    For more information on the usage of AvaTax Sale Tax Automation with X-Cart Multivendor, see {% link "AvaTax Sales Tax Automation: Usage with Multivendor" ref_3MSUEwVA %}.
    
6.  If the option to create coupons and discounts has been enabled for the vendor by the store administrator, the vendor can create coupons and discounts for their products. See {% link "Adding coupons and discounts for vendor products" ref_SwbyhUn5 %}.

7. Once customers start buying products owned by the vendor, the vendor will be able to view the orders via the Orders section. They will also have access to sales statistics including their order statistics and best selling products. See {% link "Vendor access to orders and statistics" ref_Q16T5ZnW %}.

8. 

_Related pages:_

*   {% link "Vendor registration" ref_SkW62BgH %}
*   {% link "Managing vendor profile information as a vendor" ref_b7PTQMgf %}
*   {% link "Managing the catalog as a vendor" ref_r4mcwiho %}
*   {% link "Managing vendor shipping methods" ref_IvXmtLKI %}
*   {% link "Vendor access to orders and statistics" ref_Q16T5ZnW %}
*   {% link "Vendor import/export" ref_pa3oqbXz %}
