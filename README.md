<!--- © 2015 Copyright Somonar B.V. 
 <!-- This page is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">Creative Commons Attribution-NoDerivatives 4.0 International License</a>-->


![OFBiz](http://ofbiz.apache.org/images/logo.png "Apache OFBiz")&nbsp;![Braintree](https://www.braintreepayments.com/images/b_logo-black-cd903517.svg "Braintree")

# obraintree
3rd party Payment Provider Integration Solution for Braintree&trade; as a separate and optional hot-deploy component. This component enables you to configure your Braintree integration and provides templates for inclusion in your OFBiz&trade; web store.

For more information on Braintree, visit [their site, here](https://www.braintreepayments.com).

##Development
Just put the following in the svn:externals properties of the hot-deploy folder of your OFBiz implementation for a checkout:

obraintree         https://github.com/ORRTIZ/obraintree/trunk

After having updated the hot-deploy folder (to execute the checkout from the repository), you'll need to build OFBiz again (./ant build) and load the seed, seed-initial and  - optionally- demo datasets.

## Implementation
Instructions on how to implement can be found here: https://github.com/ORRTIZ/obraintree/wiki/How-to-implement
##Issues
For an overview of open and closed issue, see: [https://github.com/ORRTIZ/obraintree/issues](https://github.com/ORRTIZ/obraintree/issues)



## License
© 2015 Copyright Somonar B.V.

<a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/4.0/88x31.png" /></a><br />This page is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">Creative Commons Attribution-NoDerivatives 4.0 International License</a>.

