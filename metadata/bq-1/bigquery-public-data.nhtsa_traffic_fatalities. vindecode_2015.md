# `nhtsa_traffic_fatalities. vindecode_2015`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `state_number`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). For more info on the codes, please look at <C1/V1/D1/PC1/P1/NM1 State Number> section in the pdf: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315
* [STRING]    `state_name`
  - This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC).
* [INTEGER]   `consecutive_number`
  - This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. xxxxxx Two Characters for State Code followed by Four Characters for Case Number
* [INTEGER]   `vehicle_number`
  - This data element is the consecutive number assigned to each vehicle in the case. This data element appears on each vehicle level data file and is used in conjunction with the ST_CASE data element to merge information from vehicle level data files. 000-999 Assigned Number of Motor Vehicle
* [STRING]    `vehicle_make`
  - Contains the Polk standardized abbreviation for the OEM's vehicle make. The vehicle make generally contains what the general public usually considers to be a vehicle brand name, for example, Chrysler, Dodge, Ford, Mercury, Toyota, GMC, Chevy, etc.
* [INTEGER]   `marketing_year`
  - The marketing year defined by the OEM within which the vehicle was produced. The value contained in this attribute may not always match the calendar year in which the vehicle was actually manufactured. Many OEMs release models prior to calendar year.
* [STRING]    `vehicle_type_code`
  - A Polk assigned code that defines the type of a vehicle represented by a specific VIN. For example: M,P,C or T.
* [STRING]    `vehicle_type`
  - The description of the Polk assigned code for the vehicle type code. For example: passenger, truck, motorcycle, commercial trailer.
* [STRING]    `make_name`
  - (Make- Name) Full name of the make (i.e. Chevrolet)
* [STRING]    `model_code`
  - (Model Code) description
* [STRING]    `vehicle_trim`
  - The Trim of the vehicle
* [STRING]    `vehicle_trim_1`
  - The trim of the vehicle. This field is used when a VIN Pattern could have more than 1 trim assigned.
* [STRING]    `vehicle_trim_2`
  - The trim of the vehicle. This field is used when a VIN Pattern could have more than 2 trims assigned.
* [STRING]    `vehicle_trim_3`
  - The trim of the vehicle. This field is used when a VIN Pattern could have more than 3 trims assigned.
* [STRING]    `vehicle_trim_4`
  - The trim of the vehicle. This field is used when a VIN Pattern could have more than 4 trims assigned.
* [STRING]    `body_style_code`
  - A Polk assigned code that describes the body style of the vehicle. For example, CP=Coupe.
* [STRING]    `body_style`
  - The description of the Polk assigned code Body Style Code For example: Coupe
* [INTEGER]   `num_of_doors`
  - The number of doors the vehicle has
* [INTEGER]   `number_of_wheels`
  - The number of wheel ends on the vehicle. For example in a 6x4 configuration this would be the 6.
* [INTEGER]   `num_of_wheels_by_power_train`
  - Number of wheels driven by the power train. For example in a 6x4 configuration this would be the 4.
* [STRING]    `vehicle_manufacturer_code`
  - (Vehicle Manufacturer Name) Standard abbreviation of the name of the vehicle manufacturer, i.e. General Motors, as defined by the National Crime Information Center
* [STRING]    `vehicle_manufacturer_name`
  - (Vehicle Manufacturer Name) The name of the vehicle manufacturer, i.e. General Motors, as defined by the National Crime Information Center
* [INTEGER]   `displacement_cid`
  - (Displacement CID) displacement in cubic inches. This is a rounded, marketing value, like 302 cubic inches, instead of 4967 cc.
* [INTEGER]   `displacement_cc`
  - (Displacement CC) displacement in cubic centimeters. We intend to use this as the definitive, exact displacement value, i.e. 4967 cc.
* [STRING]    `cylinder_count_code`
  - Contains a code that represents the number of cylinders a vehicle's combustion engine can have.
* [INTEGER]   `cycle_count`
  - (Cycle Count) Refers to the cycle or stroke of an engine. 2-strokes are lightweight and simpler, but they burn oil, by design. Few cars on the road in North America are two-strokes, the last one offered was a 1967 Saab.
* [STRING]    `fuel_code`
  - (Fuel) What an internal combustion burns to move a piston in a cylinder
* [STRING]    `fuel`
  - (Fuel) description
* [STRING]    `type_of_fuel_code`
  - The type of fuel injection
* [STRING]    `type_of_fuel`
  - The type of fuel injection used by a vehicle. For example, Direct, Throttle body
* [STRING]    `carburetion_types_code`
  - Carburetion types include 'Carburetor', 'Fuel Injection', N/A
* [STRING]    `carburetion_types`
  - The description of the Polk assigned code which identifies the vehicle carburetion type. For example Carburetor, Fuel Injection, Unknown or Electric.
* [STRING]    `num_of_barrels`
  - The number of barrels on a carbureted engine.
* [INTEGER]   `gross_vehicle_weights_range_code`
  - Contains a code that identifies the Polk standard groupings of gross vehicle weights to which a vehicle may belong. This information is typically captured only for trucks.
* [STRING]    `gross_vehicle_weights_range`
  - The description for the manufacturers assigned Gross Vehicle Weight (GVW) for trucks. This rating may or may not equal the actual GVW.
* [FLOAT]     `distance_between_axles_for_base_model`
  - Contains the distance between the front and rear axles of a vehicle in inches of the base model of the vehicle.
* [STRING]    `distance_between_axles_for_particular_series`
  - Contains the longest distance between the front and rear axles of a vehicle in inches for a particular series of that vehicle.
* [INTEGER]   `front_tire`
  - (Front Tire) More specific tire description (ex. Michelin Eagle P245/40ZR)
* [INTEGER]   `front_tire_pressure`
  - (Front Tire Pressure) Vehicle Mfr. recommendation for tire pressure, in pounds/sq. in.
* [STRING]    `front_tire_size_code`
  - Describes the size of the front tire. For example '17R245'
* [STRING]    `front_tire_size`
  - (Front Tire Size Description) As in '17R245'
* [INTEGER]   `rear_tire`
  - (Rear Tire) More specific tire description (ex. Michelin Eagle P245/40ZR)
* [INTEGER]   `rear_tire_pressure`
  - (Rear Tire Pressure) Vehicle Mfr. recommendation for tire pressure, in pounds/sq. in.
* [STRING]    `rear_tire_size_code`
  - The size of the rear tires. example '17R245'
* [STRING]    `rear_tire_size`
  - (Rear Tire Size Description) As in '17R245'
* [STRING]    `tonnage_rating`
  - (Tonnage Rating) description
* [STRING]    `shipping_weight`
  - Contains the base weight of the vehicle, rounded to the nearest one hundred pounds, as defined in the OEM's specifications. The base weight of a vehicle is the empty weight of the base model of the vehicle (i.e., the stripped down version of the vehicle)
* [STRING]    `base_price`
  - Contains the base price of the vehicle as designated by the OEM's specifications. BASE PRICE includes only the price for the base model of the vehicle, excluding any optional equipment that may have been added as a result of the vehicle's TRIM LEVEL.
* [STRING]    `drive_type_1`
  - (Drive Type) This element describes type of driving configuration for cars and trucks such as FWD, AWD, RWD.
* [STRING]    `drive_type_2`
  - (Drive Type) description
* [STRING]    `country_sold_code`
  - (Country Sold / Specific Market) Country where the vehicle is planned to be sold (may have different emissions standards).
* [STRING]    `country_sold`
  - (Country Sold / Specific Market) description
* [STRING]    `brakes_abs_code`
  - (Brakes- ABS Code) A code that describes whether a vehicle has or does not have anti-lock brakes, and what kind of brakes they are. (Not coded for heavy truck). This is based on the series code that is assigned the vehicle from VINA.
* [STRING]    `brakes_abs_description`
  - (Brakes- ABS Code) description
* [STRING]    `security_type_code`
  - (Security Type) Describes the security system (if any) installed on this model.
* [STRING]    `security_type`
  - (Security Type) description
* [STRING]    `daytime_running_lights_1`
  - (Daytime Running Lights)A Polk assigned code that identifies whether or not the vehicle has daytime running lights.
* [STRING]    `daytime_running_lights_2`
  - (Daytime Running Lights) description
* [STRING]    `restraint_type_code`
  - (Restraint Type) A Polk assigned code that identifies the type of restraints that a vehicle has based on VIN.
* [STRING]    `restraint_type`
  - (Restraint Type) description
* [STRING]    `cab_configuration_code`
  - (Cab Configuration) Cab Type describes the physical configuration of a truck's cabin.
* [STRING]    `cab_configuration`
  - (Cab Configuration) medium description
* [STRING]    `axle_type_front_axle_code`
  - (Axle- Type, Front Axle) The location of the front axle of a truck tractor. Set forward increases stability on the highway, Setback increases maneuverability in tight spaces.
* [STRING]    `axle_type_front_axle`
  - (Axle- Type, Front Axle) short description
* [STRING]    `axle_type_rear_axle_code`
  - (Axle- Type, Rear Axle) Represents rear axle configuration on a truck tractor. Tandem axles increase load bearing capability.
* [STRING]    `axle_type_rear_axle`
  - (Axle- Type, Rear Axle) short description
* [STRING]    `brake_type_code`
  - (Brake Type) The type of brakes on the Vehicle (currently commercial truck only). Truck VIN determines this currently
* [STRING]    `brake_type`
  - (Brake Type) description
* [STRING]    `engine_manufacture_code`
  - (Mfr.) A Polk assigned code given to the original equipment manufacture of the within a vehicle
* [STRING]    `engine_manufacture`
  - (Mfr.) description
* [STRING]    `engine_model`
  - (Model) description
* [STRING]    `duty_type_code`
  - (Duty Type) A Polk assigned code that represents the duty type of a truck engine, based on manufacturer information.
* [STRING]    `duty_type`
  - (Duty Type) medium description
* [STRING]    `bed_length_code`
  - (Bed Length) Code representing the manufacturer's description of the relative size of the cargo area of a pickup truck or van. A 'long' Ford Ranger bed (compact pickup) may well be shorter than a 'short' bed on an F350 (large industrial pickup).
* [STRING]    `bed_length`
  - (Bed Length) description
* [STRING]    `standard_segmentation_code`
  - The Polk standard segmentation code
* [STRING]    `standard_segmentation`
  - Description of SEGMENTATION_CODE that represents the Polk Standard Segmentation applied.
* [STRING]    `plant_code`
  - (Plant Code) Plant code where vehicle was manufactured.
* [STRING]    `plant_country`
  - (Country) This is the country where the plant is located. Example values are USA, Canada and Japan.
* [STRING]    `plant_city`
  - (City) This is the city where the plant is located.
* [STRING]    `plant_country_code`
  - A code representing the country the plant is in.
* [STRING]    `plant_state_code`
  - A code representing the state or province the plant is in.
* [STRING]    `plant_state`
  - (State or Province) This is the state or province (Canada) location of the plant.
* [STRING]    `origin_code`
  - (Origin) A code that indicates the origin of a vehicle.
* [STRING]    `origin`
  - (Origin) description
* [FLOAT]     `displacement_liters`
  - (Displacement Liters) displacement in rounded Liters, where 1,000 cubic centimeters = 1 liter. Even domestic makes will advertise displacement in terms of liters (e.g. 5.0 liter mustang, which equates to a 302 CID or 4967 cc displacement).
* [STRING]    `block_type`
  - (Block Type) Description
* [STRING]    `head_configuration_1`
  - (Head Configuration) Describes the cylinder head's camshaft/valve configuration.
* [STRING]    `head_configuration_2`
  - (Head Configuration) description
* [INTEGER]   `valves_per_cylinder`
  - (Valves Per Cylinder) Number of intake/exhaust valves per cylinder.
* [INTEGER]   `valves_total`
  - (Valves Total) Total number of intake/exhaust valves.
* [STRING]    `engine_code`
  - (Code) Code derived from the VIN (not the secondary VIN for a motorcycle). Usually a single character, some manufactures give full positions 4-8 and engine information from that; they do not break it down any further.
* [STRING]    `is_incomplete`
  - Indicator that signifies whether the vehicle is consider 'incomplete' (Y/N)
* [STRING]    `battery_type_code`
  - A value that identifies the kind of battery in the vehicle. For example: PbA- Lead Acid, NMH- Nickel Metal Hydride.
* [STRING]    `battery_type`
  - The description of the Polk assigned code for the Battery Type Code. For example: PbA- Lead Acid, NMH- Nickel Metal Hydride.
* [STRING]    `total_battery_power`
  - The measure of total battery power expressed in kilowatts. For example: 71KW, 85KW, 75KW, 67KW.
* [STRING]    `battery_voltage`
  - The voltage rating of the battery as provided by the manufacturer.
* [STRING]    `supercharge_flag`
  - Indicates if the engine has a supercharger or not.
* [STRING]    `supercharge_flag_description`
  - Indicates if the engine has a supercharger or not. Yes, No or Unknown.
* [STRING]    `turbocharger_flag`
  - Indicates if the engine has a turbocharger
* [STRING]    `turbocharger_flag_description`
  - Indicates if the engine has a turbocharger. Yes, No or Unknown.
* [STRING]    `variable_valve_timing_flag`
  - Used to determine if a car has Variable Valve Timing
* [STRING]    `motorcycles_body_style_code`
  - A further breakdown of body style for motorcycles to indicate if is it On-Road or Off-Road.
* [STRING]    `motorcycles_body_style`
  - A further breakdown of body style for motorcycles to indicate if is it On-Road or Off-Road.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
