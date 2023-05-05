# Main_Library


Warehouse Listing Description
Part Number Breakdown: 
     _ _ _       _ _ _           _ _ _        @      _ _ _          _ _ _ _   -     _ 
   Warehouse     Section         Shelf               Crate       Item Number      Version
  (3 adigits)  (3 adigits)    (3 adigits)         (3 Leters)      (4 digits)     (1 letter)

Part Categories, Subclasses and IDs:
Warehouse: A00 - Z99
Section:   A00 - Z99
Shelf:     A00 - Z99



Part Numbering and Versions:
Crate              AAA - ZZZ
Item Number        1000 - 9999
  used to count items in crate:
  > Library Entry                1000
  > Manifest                     1001
  > Revision History             9999
Versions: A - Z




Warehouse Hierarchy
Warehouse (s)
  |
  L _ _  Section (s)
  |       L _ _  Shelf (s)
  |           	  L _ _ Crate (s)
  |           	 	       L _ _  Item (s)
  |                      L_ _ Manifest 
  |                      L _ _Revision History
  |
  L _ _  Change History

