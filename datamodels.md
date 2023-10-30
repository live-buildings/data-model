# CrossDomain

Some cross-domain properties.
-  `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.
   -  Attribute type: **Property**. 
   -  Optional
-  `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.
   -  Attribute type: **Property**. 
   -  Optional



# PostalAddress

The mailing address of the item
-  `addressCountry`: Property. The country. For example, Spain. Model:'https://schema.org/addressCountry'. In french 'Pays'
   -  Attribute type: **Property**. 
   -  Optional
-  `addressRegion`: Property. The region in which the locality is, and which is in the country. Model:'https://schema.org/addressRegion'. In french 'Region'
   -  Attribute type: **Property**. 
   -  Optional
-  `addressDepartment`: Property. The department in which the locality is, and which is in the region. In french 'Departement'
   -  Attribute type: **Property**. 
   -  Optional
-  `addressLocality`: Property. The locality in which the street address is, and which is in the region. Model:'https://schema.org/addressLocality'. In french 'Commune'
   -  Attribute type: **Property**. 
   -  Optional
-  `postOfficeBoxNumber`: Property. The post office box number for PO box addresses. For example, 03578. Model:'https://schema.org/postOfficeBoxNumber'
   -  Attribute type: **Property**. 
   -  Optional
-  `postalCode`: Property. The postal code. For example, 24004. Model:'https://schema.org/https://schema.org/postalCode'. In french 'Code Postal'
   -  Attribute type: **Property**. 
   -  Optional
-  `streetAddress`: Property. The street address. Model:'https://schema.org/streetAddress'. In french: 'Numero et rue'
   -  Attribute type: **Property**. 
   -  Optional



# Organization

An organization such as a school, NGO, corporation, club, etc, mapped from schema.org
-  `address`: The mailing address of the item
   -  Attribute type: **Property**. [address](https://schema.org/address)
   -  Optional
-  `aggregateRating`: The average rating based on multiple ratings or reviews. Privacy:'low'
   -  Attribute type: **Property**. 
   -  Optional
-  `alternateName`: An alternative name for this item
   -  Attribute type: **Property**. 
   -  Optional
-  `areaServed`: The geographic area where a service or offered item is provided
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `author`: The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably.
   -  Attribute type: **Relationship**. [URL](https://schema.org/URL)
   -  Optional
-  `bestRating`: The highest value allowed in this rating system. If bestRating is omitted, 5 is assumed.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.
   -  Attribute type: **Property**. 
   -  Optional
-  `dateCreated`: Entity creation timestamp. This will usually be allocated by the storage platform.
   -  Attribute type: **Property**. 
   -  Optional
-  `dateModified`: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.
   -  Attribute type: **Property**. 
   -  Optional
-  `description`: A description of this item
   -  Attribute type: **Property**. 
   -  Optional
-  `id`: Unique identifier of the entity
   -  Attribute type: **Property**. 
   -  Required
-  `legalName`: The official name of the organization, e.g. the registered company name.
   -  Attribute type: **Property**. [legalName](https://schema.org/legalName)
   -  Optional
-  `location`: Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon
   -  Attribute type: **GeoProperty**. 
   -  Optional
-  `name`: The name of this item.
   -  Attribute type: **Property**. 
   -  Optional
-  `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)
   -  Attribute type: **Property**. 
   -  Optional
-  `reviewAspect`: This Review or Rating is relevant to this part or facet of the itemReviewed
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.
   -  Attribute type: **Property**. 
   -  Optional
-  `taxID`: The Tax / Fiscal ID of the organization or person, e.g. the TIN in the US or the CIF/NIF in Spain.
   -  Attribute type: **Property**. [taxID](https://schema.org/taxID)
   -  Optional
-  `type`: NGSI entity type. It has to be Organization. One of : `Organization`.
   -  Attribute type: **Property**. 
   -  Required
-  `url`: URL which provides a description or further information about this item.
   -  Attribute type: **Property**. 
   -  Optional
-  `headOffice`: Relationship to the head office Building of the organization.
   -  Attribute type: **Relationship**. [URL](https://schema.org/URL)
   -  Optional



# Site

A part of the physical world or a virtual world that is inherently both located in this world and having a 3D spatial extent. It is intended to contain or contains one or more buildings.
-  `id`: Unique identifier of the entity
   -  Attribute type: **Property**. 
   -  Required
-  `type`: NGSI Entity type. One of : `Site`.
   -  Attribute type: **Property**. 
   -  Required
-  `shortId`: A short id of this item. Typically an UID that uniquely identifies this item among all items of same type.
   -  Attribute type: **Property**. 
   -  Optional
-  `name`: The name of this item.
   -  Attribute type: **Property**. 
   -  Optional
-  `shortName`: A short name for this item. Typically for display purpose.
   -  Attribute type: **Property**. 
   -  Optional
-  `alternateName`: An alternative name for this item
   -  Attribute type: **Property**. 
   -  Optional
-  `category`: Category of the item. Enum:'commercial, industrial, office, parking, residential, retail, service, technical, warehouse'
   -  Attribute type: **Property**. 
   -  Optional
-  `address`: The mailing address of the item
   -  Attribute type: **Property**. [address](https://schema.org/address)
   -  Optional
-  `location`: Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon
   -  Attribute type: **GeoProperty**. 
   -  Optional
-  `areaServed`: The geographic area where a service or offered item is provided
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.
   -  Attribute type: **Property**. 
   -  Optional
-  `description`: A description of this item
   -  Attribute type: **Property**. 
   -  Optional
-  `openingHours`: Opening hours of this place.
   -  Attribute type: **Property**. [openingHours](https://schema.org/openingHours)
   -  Optional
-  `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)
   -  Attribute type: **Property**. 
   -  Optional
-  `occupier`: Person or entity using the place.
   -  Attribute type: **Property**. 
   -  Optional
-  `peopleCapacity`: Allowed people present at the place.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `employeeCount`: Number of employees attached to this place.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `individualWorkstationCount`: Number of individual workstations available in this place. An individual workstation is a workstation assigned or dedicated to a particular person.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `flexWorkstationCount`: Number of flex workstations available in this place. A flex workstation is a workstation that is not assigned or dedicated to a particular person, and can be used alternatively by different people.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `peopleOccupancy`: People present at the place.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `refMap`: Reference to the map containing the item.
   -  Attribute type: **Relationship**. 
   -  Optional
-  `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.
   -  Attribute type: **Property**. 
   -  Optional



# Building

Information on a given Building
-  `id`: Unique identifier of the entity
   -  Attribute type: **Property**. 
   -  Required
-  `type`: NGSI Entity type. One of : `Building`.
   -  Attribute type: **Property**. 
   -  Required
-  `shortId`: A short id of this item. Typically an UID that uniquely identifies this item among all items of same type.
   -  Attribute type: **Property**. 
   -  Optional
-  `name`: The name of this item.
   -  Attribute type: **Property**. 
   -  Optional
-  `shortName`: A short name for this item. Typically for display purpose.
   -  Attribute type: **Property**. 
   -  Optional
-  `alternateName`: An alternative name for this item
   -  Attribute type: **Property**. 
   -  Optional
-  `category`: Category of the item. Enum:'commercial, industrial, office, parking, residential, retail, service, technical, warehouse'
   -  Attribute type: **Property**. 
   -  Optional
-  `address`: The mailing address of the item
   -  Attribute type: **Property**. [address](https://schema.org/address)
   -  Optional
-  `location`: Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon
   -  Attribute type: **GeoProperty**. 
   -  Optional
-  `areaServed`: The geographic area where a service or offered item is provided
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.
   -  Attribute type: **Property**. 
   -  Optional
-  `description`: A description of this item
   -  Attribute type: **Property**. 
   -  Optional
-  `openingHours`: Opening hours of this building.
   -  Attribute type: **Property**. [openingHours](https://schema.org/openingHours)
   -  Optional
-  `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)
   -  Attribute type: **Property**. 
   -  Optional
-  `occupier`: Person or entity using the place.
   -  Attribute type: **Property**. 
   -  Optional
-  `peopleCapacity`: Allowed people present at the place
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `employeeCount`: Number of employees attached to this place.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `individualWorkstationCount`: Number of individual workstations available in this place. An individual workstation is a workstation assigned or dedicated to a particular person.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `flexWorkstationCount`: Number of flex workstations available in this place. A flex workstation is a workstation that is not assigned or dedicated to a particular person, and can be used alternatively by different people.
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `peopleOccupancy`: People present at the place
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `refMap`: Reference to the map containing the building
   -  Attribute type: **Relationship**. 
   -  Optional
-  `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.
   -  Attribute type: **Property**. 
   -  Optional
-  `floorsAboveGround`: Floors above the ground level
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `floorsBelowGround`: Floors below the ground level
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional



## Examples

### OK


#### Key-Values Pairs

```json
null
```

#### Normalized NGSI-LD

```json
null
```
