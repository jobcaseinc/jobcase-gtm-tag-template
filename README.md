## README

### Jobcase, Inc. Partner Action Tracking Tag Setup

#### Steps to implementation the tag.
1. Start by creating a new tag. In the tag configuration => choose tag type, search for **"Jobcase, Inc. Partner Action Tracking Tag"** custom tag
![Choose custom template tag](images/choose.custom.template.tag.png)

  * Add trigger named ex: "Jobcase Tag Landing PageView trigger" of **Page View** trigger type and add conditions
"Page URL" contains "ikey="
and
"Page URL" contains "akey="
![Configure landing page trigger](images/configure.landing.page.trigger.png)
Save the Tag as "Jobcase Landing Action Tracking Tag"
![Configure landing page tag](images/configure.landing.page.tag.png)

2. Similar to step1, import **"Jobcase, Inc. Partner Action Tracking Tag"** custom tag,but set the
 **Tag Type = Conversion**
 and
 **Custom Action Name = {Partner Configured Action Name}** (ex: apply)
 Configure the trigger action corresponding to the action taken by the user.
![Configure conversion page action trigger](images/configure.conversion.page.tag.png)
