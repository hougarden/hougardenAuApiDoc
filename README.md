## Access for current Squiiz APIs needed:

### /getListingbyID/
### /suburb/


## More information formatted needed in Apis which to be developed:

### /getAgents/ or ( /getAgentIds/ with /getAgentById/ )
#### return all available agents with Agent columns (Including officeId)

### /getOffices/ or ( /getOfficeIds/ with /getOfficeById/ )
#### return all available offices with Office columns

### /streetType/ (optional)
#### return all available streetTypes formatted

### /propertyType/ (optional)
#### return all available propertyTypes formatted


## More field of Listing Format needed if available

### Open Homes Information
#### eg: openHomeDates, isOpenHome

### floorArea rather than landSize

### listAt
#### the date when the listings be published

### listNo
#### the listing number from agency

### videoUrl

### externalUrl
#### a link to this listing on the agency website

### yearBuilt
#### the year of construction


## We will provide you with a HTTP API used for accept listing post / update action:
### Please call this API to transfer the updated information of listings when there is a new listing published or field values changed.
### You may put the JSON / XML formatted data accordding to the REA format or Squiiz Listing Format into post body.