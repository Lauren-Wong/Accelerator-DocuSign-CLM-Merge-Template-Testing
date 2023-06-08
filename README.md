# Accelerator-DocuSign-CLM-Merge-Template-Testing
This is an accelerator for testing DocuSign CLM merge templates for heavy merge tag revisions. 

**What does this solve for?**
You are troubleshooting merge template tag issues and/or formatting, and do not want to re-initiate an agreement workflow each time for testing.  
This accelerator will make it easier & faster to test updates to the merge template without requiring access to the originating system and/or making an API call.  

**Pre-Requisites**
You will need a DocuSign Developer Account with CLM access.  

**Installation Instructions:**
1. Install the spackage into your DocuSign CLM developer account. Guidance: https://support.docusign.com/s/document-item?language=en_US&bundleId=pxt1643324456371&topicId=jib1576609934581.html&_LANG=enus
2. Add "Merge Template Testing" to your Actions Menu.  Guidance: https://support.docusign.com/s/document-item?language=en_US&bundleId=pxt1643324456371&topicId=ufi1576610029380.html&_LANG=enus
  a) From Admin > Navigation & Actions, add a new Document Generation to the Actions Menu.  Select the Merge Template Tester document generation to add to the Actions Menu.  

**Testing Instructions:**
1. Within Documents, navigate to "Template Tester" > "GroupBy Merge Testing".  Confirm there is an XML file in this GroupBy folder.  
  a) If not present, add "GroupTag.xml" file to this folder.  
2.  Start the Merge Template Tester.  From the Actions menu, select Merge Template Tester.  Select the GroupTag.xml file for the XML File, and attach the GroupTag.docx for the Merge Template.  
3.  In Tasks, you should have a task assignment to review the merged document based on the XML file and Merge Template provided.  
4.  To test a change to the merge template, edit the Merge Template (e.g. Using DocuSign Edit, Office Online, or Checking In/ Uploading a new version).  Re-generate document and review again. 
