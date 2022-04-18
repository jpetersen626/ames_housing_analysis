# Project 2 - Ames Housing Data and Kaggle Challenge
---
### Problem Statement

Home-flipping has been increasingly trendy over the years, thanks in part to HGTV airing all of those home-flipping shows. These home-flippers need to decide what to renovate in the home before turning it around for the sale. This project aims to identify the features that bring the most value to a home, and which are best to improve before selling for the best possible profit.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**id**|*int64*|train_cleaned|Observation number.|
|**pid**|*int64*|train_cleaned|Parcel identification number  - can be used with city web site for parcel review.|
|**ms_subclass**|*int64*|train_cleaned|Identifies the type of dwelling involved in the sale.|
|**ms_zoning**|*object*|train_cleaned|Identifies the general zoning classification of the sale.|
|**lot_frontage**|*float64*|train_cleaned|Linear feet of street connected to property.|
|**lot_area**|*int64*|train_cleaned|Lot size in square feet.|
|**street**|*object*|train_cleaned|Type of road access to property.|
|**alley**|*object*|train_cleaned|Type of alley access to property.|
|**lot_shape**|*int64*|train_cleaned|General shape of property.|
|**land_contour**|*object*|train_cleaned|Flatness of the property.|
|**utilities**|*int64*|train_cleaned|Type of utilities available.|
|**lot_config**|*object*|train_cleaned|Lot configuration.|
|**land_slope**|*int64*|train_cleaned|Slope of property.|
|**neighborhood**|*object*|train_cleaned|Physical locations within Ames city limits.|
|**condition_1**|*object*|train_cleaned|Proximity to various conditions.|
|**condition_2**|*object*|train_cleaned|Proximity to various conditions (if more than one is present).|
|**bldg_type**|*object*|train_cleaned|Type of dwelling.|
|**house_style**|*object*|train_cleaned|Style of dwelling.|
|**overall_qual**|*int64*|train_cleaned|Rates the overall material and finish of the house.|
|**overall_cond**|*int64*|train_cleaned|Rates the overall condition of the house.|
|**year_built**|*int64*|train_cleaned|Original construction date.|
|**year_remod/add**|*int64*|train_cleaned|Remodel date (same as construction date if no remodeling or additions).|
|**roof_style**|*object*|train_cleaned|Type of roof.|
|**roof_matl**|*object*|train_cleaned|Roof material.|
|**exterior_1st**|*object*|train_cleaned|Exterior covering on house.|
|**exterior_2nd**|*object*|train_cleaned|Exterior covering on house (if more than one material).|
|**mas_vnr_type**|*object*|train_cleaned|Masonry veneer type.|
|**mas_vnr_area**|*float64*|train_cleaned|Masonry veneer area in square feet.|
|**exter_qual**|*int64*|train_cleaned|Evaluates the quality of the material on the exterior.|
|**exter_cond**|*int64*|train_cleaned|Evaluates the present condition of the material on the exterior.|
|**foundation**|*object*|train_cleaned|Type of foundation.|
|**bsmt_qual**|*float64*|train_cleaned|Evaluates the height of the basement.|
|**bsmt_cond**|*float64*|train_cleaned|Evaluates the general condition of the basement.|
|**bsmt_exposure**|*float64*|train_cleaned|Refers to walkout or garden level walls.|
|**bsmtfin_type_1**|*float64*|train_cleaned|Rating of basement finished area.|
|**bsmtfin_sf_1**|*float64*|train_cleaned|Type 1 finished square feet.|
|**bsmtfin_type_2**|*float64*|train_cleaned|Rating of basement finished area (if multiple types).|
|**bsmtfin_sf_2**|*float64*|train_cleaned|Type 2 finished square feet.|
|**bsmt_unf_sf**|*float64*|train_cleaned|Unfinished square feet of basement area.|
|**total_bsmt_sf**|*float64*|train_cleaned|Total square feet of basement area.|
|**heating**|*object*|train_cleaned|Type of heating.|
|**heating_qc**|*int64*|train_cleaned|Heating quality and condition.|
|**central_air**|*object*|train_cleaned|Central air conditioning.|
|**electrical**|*int64*|train_cleaned|Electrical system.|
|**1st_flr_sf**|*int64*|train_cleaned|First Floor square feet.|
|**2nd_flr_sf**|*int64*|train_cleaned|Second floor square feet.|
|**low_qual_fin_sf**|*int64*|train_cleaned|Low quality finished square feet (all floors).|
|**gr_liv_area**|*int64*|train_cleaned|Above grade (ground) living area square feet.|
|**bsmt_full_bath**|*float64*|train_cleaned|Basement full bathrooms.|
|**bsmt_half_bath**|*float64*|train_cleaned|Basement half bathrooms.|
|**full_bath**|*int64*|train_cleaned|Full bathrooms above grade.|
|**half_bath**|*int64*|train_cleaned|Half baths above grade.|
|**bedroom_abvgr**|*int64*|train_cleaned|Bedrooms above grade (does NOT include basement bedrooms).|
|**kitchen_abvgr**|*int64*|train_cleaned|Kitchens above grade.|
|**kitchen_qual**|*int64*|train_cleaned|Kitchen quality.|
|**totrms_abvgrd**|*int64*|train_cleaned|Total rooms above grade (does not include bathrooms).|
|**functional**|*int64*|train_cleaned|Home functionality (Assume typical unless deductions are warranted).|
|**fireplaces**|*int64*|train_cleaned|Number of fireplaces.|
|**fireplace_qu**|*int64*|train_cleaned|Fireplace quality.|
|**garage_type**|*object*|train_cleaned|Garage location.|
|**garage_yr_blt**|*float64*|train_cleaned|Year garage was built.|
|**garage_finish**|*float64*|train_cleaned|Interior finish of the garage.|
|**garage_cars**|*float64*|train_cleaned|Size of garage in car capacity.|
|**garage_area**|*float64*|train_cleaned|Size of garage in square feet.|
|**garage_qual**|*float64*|train_cleaned|Garage quality.|
|**garage_cond**|*float64*|train_cleaned|Garage condition.|
|**paved_drive**|*int64*|train_cleaned|Paved driveway.|
|**wood_deck_sf**|*int64*|train_cleaned|Wood deck area in square feet.|
|**open_porch_sf**|*int64*|train_cleaned|Open porch area in square feet.|
|**enclosed_porch**|*int64*|train_cleaned|Enclosed porch area in square feet.|
|**3ssn_porch**|*int64*|train_cleaned|Three season porch area in square feet.|
|**screen_porch**|*int64*|train_cleaned|Screen porch area in square feet.|
|**pool_area**|*int64*|train_cleaned|Pool area in square feet.|
|**pool_qc**|*int64*|train_cleaned|Pool quality.|
|**fence**|*int64*|train_cleaned|Fence quality.|
|**misc_feature**|*object*|train_cleaned|Miscellaneous feature not covered in other categories.|
|**misc_val**|*int64*|train_cleaned|$Value of miscellaneous feature.|
|**mo_sold**|*int64*|train_cleaned|Month Sold (MM).|
|**yr_sold**|*int64*|train_cleaned|Year Sold (YYYY).|
|**sale_type**|*object*|train_cleaned|Type of sale.|
|**saleprice**|*int64*|train_cleaned|Sale price $$.|

For more information about the data, refer to the original data dictionary from the data set here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt.

### Summary of Analysis

When first looking at the data, I just looked at all correlations between the different numerical and categorical values against sale price to find relationships. I mostly focused on the features in the data that corresponded to things that could be renovated. Once I had a list of the features that seemed to have an impact on sale price, I built a model based around those features to predict housing price to see which ones had the strongest positive or negative impact. The model was then tuned up for optimal results.

### Conclusions/Recommendations

Based on the coefficients of the model, as well as exploration of the data before the model, I discovered that there were definitely some features that add significant value to the home. Each number that came out of the model was representative of the numerical impact on sale price if only that one feature was changed, and all else stayed constant. 

The main features that really add value to the home are the material and finish of the house, the roof material, the square footage of the home, the number of bathrooms above grade, fireplace quantity and quality, garage space and the type of garage, the house foundation, having a separate basement entrance or window, and a paved driveway. Any number or combination of those features should be explored for renovations when home-flippers are deciding what to do and tackle. Of course, which features that are ultimately chosen to work on will depend on many factors that only the home-flippers themselves will know, such as the state of the house that is going to be flipped when it comes into their possession.

Knowing this information will likely benefit stakeholders in the home-flipping business. This is because knowing how much value a feature can add to a home is valuable information that allows those with a budget to really focus on what’s important for the best sale price possible. For furthering this project, other features in the model could be explored further to assess whether there is some multicollinearity that potentially pushed some features to the side in favor of these ones. If that is the case, there is a possibility that some of those features are equally as profitable to focus on, but the model just chose a different feature in its stead. 