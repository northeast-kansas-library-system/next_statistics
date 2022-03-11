# next_statistics

# 2022 Instructions

## Monthly overview
- 2022 monthly overview (Excel file)
- Filename = \2022\2022.a.monthly_overview.xlsx
  - Run reports:
    - 3418
    - 3419
    - 3420
    - 3421
    - 3422
  - Paste data into hidden sheets in file (February data goes into FebruaryRaw, March data goes into MarchRaw, etc.)


- FY 2021/2022 monthly overview (Excel file)
- Filename = \2022.a.monthly_overview.fy.xlsx
  - take the data pasted into 2022 monthly overview (Excel file) and process it through \excel_tools\convert_raw_to_2022_fiscal.xlsx if needed
  - then put the data into \2022\2022.a.monthly_overview.fy.xlsx

## Circulation by library details
- Hourly statistics (Excel file)
- Filename = \2022\2022.b.circ_by_library.hourly.xlsx?raw=true
  - Run report 3499 and paste data as values into this file for the appropriate month

## Circulation by item details
- Circulation by collection code (Excel file)
- Filename = \2022\2022.c.monthly_circ_by_item.ccode.xlsx
- Run report 3394 and past data into the hidden sheets (February data goes into FebruaryRaw, March data goes into MarchRaw, etc.)


- Circulation by item type (Excel file)
- Filename = \2022\2022.c.monthly_circ_by_item.itype.xlsx
- Run report 3355 and past data into the hidden sheets (February data goes into FebruaryRaw, March data goes into MarchRaw, etc.)

## Circulation by borrower details
- Unique borrowers at your library (Excel file)
- Filename = \2022\2022.d.monthly_circ_by_borrower.unique_borrowers.xlsx
<!-- TODO: add report number -->


- Circulation by borrower's zipcode (Excel file)
- Filename = \2022\2022.d.monthly_circ_by_borrower.zipcode.xlsx
<!-- TODO: add report number -->

## Borrower statistics
- Borrower count by borrower category (Excel file)
- Filename = \2022\2022.e.borrower_count.category.xlsx
<!-- TODO: add report number -->


- Borrower count by zip code (Excel file)
- Filename = \2022\2022.e.borrower_count.zipcode.xlsx
<!-- TODO: add report number -->

## Items and holdings statistics
- Item count by item type (Excel file)
- Filename = \2022\2022.f.item_count.ccode.xlsx
<!-- TODO: add report number -->


- Item county by collection code (Excel file)
- Filename = \2022\2022.f.item_count.itype.xlsx
<!-- TODO: add report number -->

## Request and sharing statistics
- In progress
- Filename =
<!-- TODO: add report number -->


- In progress
- Filename =
<!-- TODO: add report number -->

## Electronic materials statistics

- Robin manages this page - all you need to do is update the date on intranetmain

## Detailed statistical reports

NEKLS does not run these reports for libraries.  They may run them on their own if they desire the data.

- Checkout and renewal count by item type and shelving location - previous calendar month - Link runs report 3128
- Checkout and renewal count by collection code and shelving location - previous calendar month - Link runs report 2902
- Materials added count by item type and location - previous calendar month - Link runs report 2901
- Materials added count by collection code and location - previous calendar month - Link runs report 3361
- Borrower counts by category: total borrowers plus borrower added, renewed, and deleted - previous calendar month - Link runs report 3128

## Next Search Catalog 2022 overall statistics

- Data for this table is generated in \2022\2022.a.monthly_overview.xlsx on the worksheet titled "Intranetmain"
- Paste the data from the column for the current month into the table inside the div #stats_table in the system preference "IntranetmainUserblock"
- Once this data has been pasted, remove the "currow" class from the previous month's row

## Graph of circulation by month over time
- Use \2022\2022.z.graph.xlsx to generate the image used here
- The image from Excel can be converted to a png with GIMP or Microsoft Paint
- Once the image is converted to a png, add a border in SnagIt
- Once the image has a border, use pnguy to shrink the png file so loading is uses as little bandwidth as possible
- Then upload it to the \images folder here and give it the appropriate month
