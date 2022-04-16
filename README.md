# Project 2 - Ames Housing Data and Kaggle Challenge
---
### Problem Statement


### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**id**|*int64*|train|Observation number.|
|**pid**|*int64*|train|Parcel identification number  - can be used with city web site for parcel review.|
|**ms_subclass**|*int64*|train|Identifies the type of dwelling involved in the sale.|
|**ms_zoning**|*object*|train|Identifies the general zoning classification of the sale.|
|**lot_frontage**|*float64*|train|Linear feet of street connected to property.|
|**lot_area**|*int64*|train|Lot size in square feet.|
|**street**|*object*|train|Type of road access to property.|
|**alley**|*object*|train|Type of alley access to property.|
|**lot_shape**|*int64*|train|General shape of property.|
|**land_contour**|*object*|train|Flatness of the property.|
|**utilities**|*int64*|train|Type of utilities available.|
|**lot_config**|*object*|train|Lot configuration.|
|**land_slope**|*int64*|train|Slope of property.|
|**neighborhood**|*object*|train|Physical locations within Ames city limits.|
|**condition_1**|*object*|train|Proximity to various conditions.|
|**condition_2**|*object*|train|Proximity to various conditions (if more than one is present).|
|**bldg_type**|*object*|train|Type of dwelling.|
|**house_style**|*object*|train|Style of dwelling.|
|**overall_qual**|*int64*|train|Rates the overall material and finish of the house.|
|**overall_cond**|*int64*|train|Rates the overall condition of the house.|
|**year_built**|*int64*|train|Original construction date.|
|**year_remod/add**|*int64*|train|Remodel date (same as construction date if no remodeling or additions).|
|**roof_style**|*object*|train|Type of roof.|
|**roof_matl**|*object*|train|Roof material.|
|**exterior_1st**|*object*|train|Exterior covering on house.|
|**exterior_2nd**|*object*|train|Exterior covering on house (if more than one material).|
|**mas_vnr_type**|*object*|train|Masonry veneer type.|
|**mas_vnr_area**|*float64*|train|Masonry veneer area in square feet.|
|**exter_qual**|*int64*|train|Evaluates the quality of the material on the exterior.|
|**exter_cond**|*int64*|train|Evaluates the present condition of the material on the exterior.|
|**foundation**|*object*|train|Type of foundation.|
|**bsmt_qual**|*float64*|train|Evaluates the height of the basement.|
|**bsmt_cond**|*float64*|train|Evaluates the general condition of the basement.|
|**bsmt_exposure**|*float64*|train|Refers to walkout or garden level walls.|
|**bsmtfin_type_1**|*float64*|train|Rating of basement finished area.|
|**bsmtfin_sf_1**|*float64*|train|Type 1 finished square feet.|
|**bsmtfin_type_2**|*float64*|train|Rating of basement finished area (if multiple types).|
|**bsmtfin_sf_2**|*float64*|train|Type 2 finished square feet.|
|**bsmt_unf_sf**|*float64*|train|Unfinished square feet of basement area.|
|**total_bsmt_sf**|*float64*|train|Total square feet of basement area.|
|**heating**|*object*|train|Type of heating.|
|**heating_qc**|*int64*|train|Heating quality and condition.|
|**central_air**|*object*|train|Central air conditioning.|
|**electrical**|*int64*|train|Electrical system.|
|**1st_flr_sf**|*int64*|train|First Floor square feet.|
|**2nd_flr_sf**|*int64*|train|Second floor square feet.|
|**low_qual_fin_sf**|*int64*|train|Low quality finished square feet (all floors).|
|**gr_liv_area**|*int64*|train|Above grade (ground) living area square feet.|
|**bsmt_full_bath**|*float64*|train|Basement full bathrooms.|
|**bsmt_half_bath**|*float64*|train|Basement half bathrooms.|
|**full_bath**|*int64*|train|Full bathrooms above grade.|
|**half_bath**|*int64*|train|Half baths above grade.|
|**bedroom_abvgr**|*int64*|train|Bedrooms above grade (does NOT include basement bedrooms).|
|**kitchen_abvgr**|*int64*|train|Kitchens above grade.|
|**kitchen_qual**|*int64*|train|Kitchen quality.|
|**totrms_abvgrd**|*int64*|train|Total rooms above grade (does not include bathrooms).|
|**functional**|*int64*|train|Home functionality (Assume typical unless deductions are warranted).|
|**fireplaces**|*int64*|train|Number of fireplaces.|
|**fireplace_qu**|*int64*|train|Fireplace quality.|
|**garage_type**|*object*|train|Garage location.|
|**garage_yr_blt**|*float64*|train|Year garage was built.|
|**garage_finish**|*float64*|train|Interior finish of the garage.|
|**garage_cars**|*float64*|train|Size of garage in car capacity.|
|**garage_area**|*float64*|train|Size of garage in square feet.|
|**garage_qual**|*float64*|train|Garage quality.|
|**garage_cond**|*float64*|train|Garage condition.|
|**paved_drive**|*int64*|train|Paved driveway.|
|**wood_deck_sf**|*int64*|train|Wood deck area in square feet.|
|**open_porch_sf**|*int64*|train|Open porch area in square feet.|
|**enclosed_porch**|*int64*|train|Enclosed porch area in square feet.|
|**3ssn_porch**|*int64*|train|Three season porch area in square feet.|
|**screen_porch**|*int64*|train|Screen porch area in square feet.|
|**pool_area**|*int64*|train|Pool area in square feet.|
|**pool_qc**|*int64*|train|Pool quality.|
|**fence**|*int64*|train|Fence quality.|
|**misc_feature**|*object*|train|Miscellaneous feature not covered in other categories.|
|**misc_val**|*int64*|train|$Value of miscellaneous feature.|
|**mo_sold**|*int64*|train|Month Sold (MM).|
|**yr_sold**|*int64*|train|Year Sold (YYYY).|
|**sale_type**|*object*|train|Type of sale.|
|**saleprice**|*int64*|train|Sale price $$.|

For more information about the data, refer to the original data dictionary from the data set here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt.

