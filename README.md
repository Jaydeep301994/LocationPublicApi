# LocationPublicApi
Sections

1.Base API Url

2.List of All Locations

3.Create location

4.Single Location

5.Update location

<h1>1.Base API Url</h1>

All endpoints described in this document with the exception of Reporting have the following base API url: https://api.places.digital/locations-api-write/

<h1>2.List of All Locations</h1>

Http Verb: GET.

Headers: Content-Type: application/json

Http EndPoint: /locations

<strong>QueryString Parameters:</strong>

```{questions}
- AccountID: (Format - uuid. The unique identifier for the Account)
- Bearer : 'Format -string. 'Passed into header for Authorization''
```


<strong>Response Json Body</strong>

```{questions}
[{
  "AccountID": "00000000-0000-0000-0000-000000000000",
  "LocationID": "00000000-0000-0000-0000-000000000000",
  "LocationNumber": "string",
  "ReferenceCode": "string",
  "CreatedBy": "string",
  "ModifiedBy": "string",
  "Created": "string",
  "Modified": "string",
  "LocationData": {
    "KeyFields": {},
    "DisplayPoint": {
      "Type": "Calculated",
      "Latitude": 0.0,
      "Longitude": 0.0,
      "VerificationType": "Client"
    },
    "BusinessStatus": "Open",
    "Status": "Active",
    "BusinessName": {
      "Name": "string",
      "LongName": "string",
      "Locale": "Not_set"
    },
    "BusinessDescription": {
      "Description": "string",
      "ShortDescription": "string",
      "LongDescription": "string"
    },
    "PrimaryAddress": {
      "AddressLine1": "string",
      "AddressLine2": "string",
      "AddressLine3": "string",
      "AddressLine4": "string",
      "AddressLine5": "string",
      "Neighborhood": "string",
      "Locality": "string",
      "Region": "string",
      "PostalCode": "string",
      "CountryCode": "string"
    },
    "PhoneNumbers": {
      "PrimaryPhoneNumber": "string",
      "Landline": "string",
      "Mobile": "string",
      "Fax": "string",
      "TollFree": "string"
    },
    "WebsiteURL": "string",
    "AlternateWebsiteURL": "string",
    "MediaURLs": {
      "FacebookURL": "string",
      "TwitterURL": "string",
      "LinkedInURL": "string",
      "InstagramURL": "string",
      "PinterestURL": "string",
      "CouponURL": "string",
      "SocialNetworkURL": "string",
      "VideoURL": "string"
    },
    "HoursOfOperation": "string",
    "HoursOfOperationStructured": {
      "SpecialHours": [
        {
          "Date": "string",
          "Ranges": [
            {
              "StartTime": "string",
              "EndTime": "string"
            }
          ],
          "State": "Open",
          "AdditionalInfo": "string"
        }
      ],
      "Su": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      },
      "Mo": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      },
      "Tu": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      },
      "We": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      },
      "Th": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      },
      "Fr": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      },
      "Sa": {
        "Ranges": [
          {
            "StartTime": "string",
            "EndTime": "string"
          }
        ],
        "State": "Open",
        "AdditionalInfo": "string"
      }
    },
    "BusinessCategories": {
      "Category1": "string",
      "Category2": "string",
      "Category3": "string",
      "Category4": "string",
      "Category5": "string",
      "Category6": "string",
      "Category7": "string",
      "Category8": "string",
      "Category9": "string",
      "Category10": "string"
    },
    "Chain": "string",
    "Amenities": "string",
    "PaymentMethods": "string",
    "PrimaryContact": {
      "FullName": "string",
      "FirstName": "string",
      "MiddleName": "string",
      "LastName": "string",
      "Title": "string",
      "EmailAddress": "string"
    },
    "EmailAddress": "string",
    "PhotoURLs": [
      {
        "Type": "ProfilePhoto",
        "URL": "string",
        "Name": "string",
        "Description": "string"
      }
    ],
    "KeywordsSpecialties": "string",
    "CredentialsCertifications": "string",
    "Products": "string",
    "Services": "string",
    "Brands": "string",
    "YearFounded": "string",
    "ProfessionalAssociations": "string",
    "Tagline": "string",
    "NumberEmployees": "string",
    "AreasServed": "string",
    "Languages": "string",
    "AlternateOrCorporateName": "string"
  },
  "UserData": {}
}]
```
