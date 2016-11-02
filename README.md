## Access for two Squiiz APIs is needed as following:

**/getListingbyID/**
**/suburb/**

## More information needs to be provided:

**/agents or ( /agents/ids with /agents/{id} )**
>return all available agents with Agent columns (Including officeId)

**/offices or ( /offices/ids with /offices/{id})**
>return all available offices with Office columns

**/streetType (optional)**
>return all available streetTypes formatted

**/propertyType (optional)**
>return all available propertyTypes formatted


## More fields of Listing Format are needed if available

**Open Homes Information**
>eg: openHomeDates, isOpenHome

**floorArea**

**listAt**
>the date when the listing is published

**listNo**
>the listing number from agency

**videoUrl**

**externalUrl**
>link of this listing on the agency website

**yearBuilt**
>year of construction

## We will provide you with a post interface used for receiving listings:
>Please call this API to transfer the updated information of listings when there are new listings published or changed.
>You may put JSON / XML formatted data according to the REA format or Squiiz Listing Format in the body.

## Questions
**Is there any other value of listingType not including Purchase and Lease?** 
