# sp-adv-list
Custom ServiceNow application for generating list of records from multiple different data sources and displaying that in Service Portal.
Display content of each record type can be customized along with linking behaviour and link parameters. 

# Installation
To be added

# How to use application

## Create a data source for a list.
### Basic details
Source name - name for this data source  
ID - unique id for this data source  
Active - inactive sources won't display in the widget  
Short description - description for the source  

### Data
Table - table where the data for this source is fetched
Filter - filter that is applied to the table
Title Field - field that is used as title for the list record
Primary display fields - fields to be displayed in the list record
Secondary display fields - fields to be displayed in the list record

### Behaviour
Type - Service Portal page or URL
Page - Service Portal page to link to
URL - Base URL to link to 
Link Parameter Fields - fields in the source table that can be used as URL parameters
Link Parameters - Name/value pairs of URL parameters that will be added to the URL when user clicks a record from this source

### Presentation
Item icon - FontAwesome icon that is displayed at the left side of the record on the list
Item template - How the data on the record is displayed in the list
    
<img width="1399" alt="Screenshot 2020-09-16 at 15 40 55" src="https://user-images.githubusercontent.com/34348034/93457590-dac99800-f8e7-11ea-889f-657bad25bf0a.png" style="max-width:100%;">
    
    
## 2. Add Advanced list widget to Service Portal page



## 3. In the widget instance options add the list sources you want to use in your list.




# Upcoming features
See list of issues in this repository
