# MAAP STAC Providers

Library of STAC provider definitions for use in the MAAP STAC.

If you are adding STAC Providers to a collection in the MAAP STAC, check this list and use an existing one if you find a suitable match.
If you do not find a match, check this [csv](https://cmr.earthdata.nasa.gov/kms/concepts/concept_scheme/providers?format=csv) and map the following fields to a new entry:

| CSV column | STAC Provider key |
| -------------- | --------------- |
| `Short_Name` | `name` |
| `Long_name` | `description` |
| `Data_Center_URL` | `url` |
