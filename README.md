# specify_views_ISA
This repository contains the customised views of Specify forms used at ISA for
the herbarium collection.

## Changes in Specify forms
The changes in the default specify forms made by these customised views are the
following:
### Collection Object form (file `botany.views.xml`)
- addition of fields
  - Collection
  - previous institution
  - other catalog number
  - project number
  - remarks
- addition of subform __Collection Object Citations__

### Collecting Event form (file `botany.views.xml`)
- addition of fields
  - verbatim date
  - verbatim locality

### Locality Detail form (file `common.views.xml`)
- addition of fields
  - island
  - provincia
  - utmZone, utmDatum, utmEasting, utmNorthing
  - X, Y, reference system

## How to install
In Specify, use the menu System --> Resource Import/Export. As the level of import, for `botany.views.xml`,select __User Type__; for `common.view.xml`, select __Institution__.
