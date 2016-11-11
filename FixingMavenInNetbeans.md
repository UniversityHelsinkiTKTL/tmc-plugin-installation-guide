# Fixing Maven in Netbeans

Some distributions of NetBeans have been stripped of Maven support. This is problematic, as it breaks dowloading and opening Manven exercises with the TestMyCode plugin. The issue seems to affect at least the default NetBeans in Ubuntu 16.04 repositories.

This document describes a way to fix the issue by installing Maven support in NetBeans.

## Instructions

Open Netbeans and open the `Plugins` dialog by selecting `Tools` > `Plugins`.

Next, navigate to the `Settings` tab and make sure `NetBeans Distribution` is selected.

![Select Netbeans Distribution](fix-maven-netbeans-images/1.png)

Then navigate to the `Available Plugins` tab, and click `Check for Newest`.

![Select Check for Newest](fix-maven-netbeans-images/2.png)

Select Maven from the list and click install. Using the search bar may help with finding the entry.

![Install maven](fix-maven-netbeans-images/3.png)

Then proceed with the installation. Once it's completed and NetBeans has restarted, downloading maven exercises should work again.

![Proceed with the installation](fix-maven-netbeans-images/4.png)
