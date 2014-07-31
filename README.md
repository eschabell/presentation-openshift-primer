Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create primer -t php-5.4 --from-code git://github.com/eschabell/presentation-openshift-primer.git

That's it, you can now start your workshop at:

    http://primer-$your_domain.rhcloud.com

![Cover Slide](https://raw.githubusercontent.com/eschabell/presentation-openshift-primer/master/cover.png)
