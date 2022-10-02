# Graylog Extractors for VyOS

This package installs Graylog Extractors for VyOS. Extractors are included for firewall, prometheus-node-exporter, and dhcp6c.

If you have anything to add, please feel free to submit a pull request.

## Installation
This package only includes extractors for now. To install, navigate to your **System** menu, then choose **Inputs**. From there, locate your Syslog input and click the **Manage extractors** button. 

Click **Actions** then **Import extractors**, and then paste the contents of graylog-vyos-extractors.json into the box on the page. Click **Add extractors to input** then click the **Back** button in your browser. You should now see all of the extractors listed. 

## Important!
Keep in mind that if you import again, you're adding to what's already there: It doesn't "update" the existing with your new import. So you'll need to delete any extractors you plan to re-import.

