# Adobe AEM on AWS

A set of AWS Cloud Formation Scripts for launching an Adobe AEM Stack using the Adobe AEM Quickstart Jar.

# single_aem_instance.template

Will launch a single EC2 instance with AEM installed in both the author and publisher run modes.
Once the cloud formation stack has compelted its run, you will need to grab the EC2 DNS name and enter it in the browser, once loaded you will be asked for your Adobe license. once completed you will be able to view the sample site in publish mode.
To view the Author mode you need to access the site via the port 4502 (default adobe port).







# Adobe Trial License

You can request a trial license directly from Adobe 

https://www.day.com/content/day/en/registration/cq-provisioning.html
