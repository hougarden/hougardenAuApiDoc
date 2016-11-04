## We need more fields of Listing Format are needed if available

**1. Open Homes Information**
>eg: openHomeDates, isOpenHome

**2. floorArea**

**3. listNo or uniqueId**
>the listing number from agency

**4. videoLink**

**5. externalLink**
>link of this listing on the agency website

**6. soldDate soldPrice soldDetails**

**7. yearBuilt**
>year of construction


## We need more interfaces to fetch data

**1. An interface to get all available agents with formatted data

**2. An interface to get all available offices with formatted data

**3. An interface to get all available Municipalities with formatted data just as the API named "/suburb/"

**4. An interface to get all property types such as House, Unit, Flat... with their slugs

**5. An interface to get all street types such as Avenue, Road, Lane... with their slugs


## Questions
**1. Is there any other value of listingType not including Purchase and Lease?**

**2. Please add two parameters (updateAfter, listAfter) in the query of API named "/listing/" or "/search/" to fetch new listings or updated listings. Otherwise we need to fetch the whole database on daily basis.**
