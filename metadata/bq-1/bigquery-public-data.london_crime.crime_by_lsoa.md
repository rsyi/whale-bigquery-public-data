# `london_crime.crime_by_lsoa`
`bq-1` | `bigquery-public-data`
This data counts the number of crimes at two different geographic levels of London (LSOA and borough) by year, according to crime type.  

Below is a list of the crime types covered (*not available at LSOA level):

Major Category: Minor Category 

Burglary: Burglary in a Dwelling (data to March 2017)

Burglary: Burglary in Other Buildings (data to March 2017)

Burglary:  Burglary - Residential (as of April 2017 Burglary in a Dwelling was changed to this subcategory to take account of certain offences being reclassified from what was the 'Other buildings' category (now Business and Community) into this new category eg. burglaries of shed and outbuildings). The old and new subcategories are therefore not comparable. 

Burglary: Burglary - Business and Community (as of April 2017 Burglary in Other Buildings was changed to this subcategory to take account of certain offences being reclassified to what is now the 'Burglary Residential' category. The old and new subcategories are therefore not comparable. 

Criminal Damage: Criminal Damage To Dwelling

Criminal Damage: Criminal Damage To Motor Vehicle

Criminal Damage: Criminal Damage To Other Building

Criminal Damage: Other Criminal Damage

Drugs: Drug Trafficking

Drugs: Other Drugs

Drugs: Possession Of Drugs

Fraud or Forgery: Counted per Victim*

Fraud or Forgery: Other Fraud & Forgery

Other Notifiable Offences: Going Equipped

Other Notifiable Offences: Other Notifiable

Robbery: Business Property

Robbery: Personal Property

Sexual Offences: Other Sexual

Sexual Offences: Rape

Theft and Handling: Handling Stolen Goods

Theft and Handling: Motor Vehicle Interference & Tampering

Theft and Handling: Other Theft

Theft and Handling: Other Theft Person

Theft and Handling: Theft From Motor Vehicle

Theft and Handling: Theft From Shops

Theft and Handling: Theft/Taking of Pedal Cycle

Violence Against the Person: Assault with Injury

Violence Against the Person: Common Assault

Violence Against the Person: Grievous Bodily Harm

Violence Against the Person: Harassment

Violence Against the Person: Murder

Violence Against the Person: Offensive Weapon

Violence Against the Person: Other violence

Violence Against the Person: Wounding/GBH

## Column details
* [STRING]    `lsoa_code`
  - Lower Layer Super Output Area code according to the Office for National Statistics
* [STRING]    `borough`
* [STRING]    `major_category`
* [STRING]    `minor_category`
* [INTEGER]   `value`
  - Summary of the number of crimes for the month
* [INTEGER]   `year`
* [INTEGER]   `month`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
