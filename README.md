# Call-Metadata-API-from-Apex

# Test Suggestion 
1. need to create an Apex class 'MetadataService' in your system
   you could generate that file by WSDL2Apex tool,
2. you can run 'create List View' sample code in the anonymous code window to create a new List View. 
3. you can also update a specific List view by running 'update List View' sample code. system will recognize list view by its API name. 


# Implementation Suggestion
one posibility is to create a Visualforce page to hold the function, 
when you click button in the vf page, it will trigger system call create/update Metadata function.<br/>
<b>CODE</b> : shareListViewVF + ListViewButtonDemo <br/>
how to dynamically get list view Id from current page? <br/>
- Answer: by use visualforce page standard controller function. 
> stdController.getFilterId();<br/>

in which filterID is list view Id from sobject list view page

