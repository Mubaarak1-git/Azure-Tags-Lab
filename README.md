# Azure Tags Lab 
In this lab, I demonstrate how to effectively tag resources in Microsoft Azure to improve the organization and management of cloud infrastructure. I use tagging to assign metadata—such as environment, department, or cost center—to resources like virtual machines, making it easier to track and categorize them.

Through a step-by-step process, I apply meaningful tags across multiple resources and use Azure’s filtering tools to display and manage assets based on their assigned tags. This lab showcases how I implement and utilize tags to enhance visibility, governance, and operational clarity within Azure.

## 🎯 Lab Objectives – Azure Tags Lab
- I explored the importance of tagging resources in Microsoft Azure to improve organization and streamline infrastructure management.

- I applied tags to Azure resources—such as virtual machines—using the Azure portal interface.

- I gained hands-on experience creating and assigning meaningful tags like "Environment" and specifying values such as "Production" and "Development".

- I used tags to filter and view resources based on specific categories, making it easier to manage workloads across my cloud environment.

- I developed practical skills in using Azure’s search functionality to locate resources by their assigned tags, enhancing visibility and operational control.

## 📸Screenshots

###  Step 1: Click DC01  
_Selected the virtual machine “DC01” from the resource list to begin tagging._

![Select Resource](Screenshots/select%20Resource.png)

### Step 2: Click Tags  
_Navigated to the “Tags” blade from the DC01 virtual machine overview to begin assigning metadata for environment classification._

![Click Tags](Screenshots/Click%20tags.png)

### Step 3: Click Name field  
_Began the tagging process by clicking into the “Name” field to define the metadata key for the DC01 virtual machine._

![Click Name field](Screenshots/Naming%20Tag.png)

### Step 4: Click Value Field  
_Entered the tag value in the “Value” field to complete the metadata pair for the DC01 virtual machine._

![Click Value Field ](Screenshots/Give%20Value.png)

###  Step 5: Type Production and press Enter  
_Entered `Production` as the tag value to classify the DC01 virtual machine under the production environment._

![Type Production and press Enter](Screenshots/Name%20and%20Value.png)

### Step 6: Confirm Tag Input
The tooltip prompts to press Enter after typing the value, confirming the tag entry.
![Select Resource](Screenshots/Apply.png)

### Step 7: Review Tag Summary
The interface shows the tag pair Environment = Development ready to be applied.
![Select Resource](Screenshots/Go%20HomeScreen.png)

### Step 8: Apply Tag
Clicked “Apply” to save the tag to the WEB01 VM, making it part of the resource metadata.
![Select Resource](Screenshots/Tag%20other%20Resource.png)

### Step 9: Validate Tag Assignment
Confirmed that the tag was successfully added and now appears in the resource’s tag list.
![Select Resource](Screenshots/Click%20tags%20on%20VM.png)

### Step 10: Repeat for Other Resources
Prepared to replicate tagging across other VMs and resources for consistent metadata management.
![Select Resource](Screenshots/Tag%20Name%20and%20Vlaue%20Fields.png)

###  Step 11: Click Apply  
_Saved the tag `Environment = Development` to the WEB01 virtual machine by clicking “Apply,” finalizing the metadata assignment._
![Click Apply](Screenshots/Apply%20Change.png)

### Step 12: Click Home  
_Returned to the Azure portal homepage by clicking “Home,” preparing to view and filter resources by tag._

![Click Home](Screenshots/Go%20Home%20Again.png)

### Step 13: Click search box  
_Used the Azure portal’s search bar to locate resources, services, or documentation relevant to tagging and virtual machine management._

![Select Resource](Screenshots/Search%20Resources%20Based%20on%20Tags.png)

### Step 14: Type tags and press enter  
_Used the Azure portal’s search bar to locate the Tags blade by typing “tags” and pressing Enter, streamlining navigation to resource metadata._

![Type tags ](Screenshots/Type%20Tags%20on%20Search.png)

### Step 15: Click Tags  
_Selected the “Tags” option from the search results to open the tagging interface and begin resource categorization._

![Click Tags  ](Screenshots/Select%20Tags%20.png)

###  Step 16: Click Environment: Development  
_Selected the tag `Environment: Development` to filter and view resources categorized under the development environment._

![Click Environment - Development](Screenshots/Click%20taged%20Resources.png)

###  Step 17: Click Environment: Production  
_Switched the tag filter to `Environment: Production` to view resources categorized under the production environment._

![Select Resource](Screenshots/Selecet%20Enviornment%20.png)

### Step 18: Click Home  
_Returned to the Azure portal homepage by clicking “Home,” resetting the view after filtering resources by the `Environment: Production` tag._

![Click Home](Screenshots/Click%20Homescreen.png)

