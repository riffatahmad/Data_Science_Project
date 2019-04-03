Goal: to Predict the Claims as Fraud or Legit

Description of the Dataset:
A 1996 auto claims fraud dataset. This dataset contains the fields:

Month			: the month in which the accident happen
WeekOfMonth		: week of the month in whihc the accident happen
DayOfWeek		: Day of the week in which the accident happen
Make			: Make of the car...['Honda', 'Toyota', 'Ford', 'Mazda', 'Chevrolet', 'Pontiac','Accura', 'Dodge', 'Mercury', 'Jaguar', 'Nisson', 'VW', 'Saab',
       					     'Saturn', 'Porche', 'BMW', 'Mecedes', 'Ferrari', 'Lexus']
AccidentArea		: accident area  [Rural or Urban]
DayOfWeekClaimed	: Day of the week claim was made
MonthClaimed		: Month of the year claim was made
WeekOfMonthClaimed	: week of the month claim was made
Sex			: sex of the insurer [Female, Male]
MaritalStatus		: MARITAL STATUS OF THE insurer ['Single','Married']
Age			: Age of the insurer... its in class intervals
Fault			: Describing the faulte party....[Policy Holder, Third Party]
PolicyType		: policy type.....['Sport - Liability', 'Sport - Collision', 'Sedan - Liability','Utility - All Perils', 'Sedan - All Perils', 'Sedan - Collision',
      					   'Utility - Collision', 'Utility - Liability', 'Sport - All Perils']
VehicleCategory		: Type of Vehicle....[Sport,Utility,Sedan]
VehiclePrice		: Vehicle Price in Range ....['more than 69,000', '20,000 to 29,000', '30,000 to 39,000','less than 20,000', '40,000 to 59,000', '60,000 to 69,000'],
FraudFound		: either fraud was found.... [yes or no]
PolicyNumber		: Policy Number in Serial
RepNumber		: ????
Deductible		: Deductible amount ......[300,400,500 or 700]
DriverRating		: Ratings of the driver......[1,2,3,4]
Days:Policy-Accident	: Number of days between Policy Bought and the Accident...its in range [more than 30', '15 to 30', 'none', '1 to 7', '8 to 15']
Days:Policy-Claim	: Number of days between Policy bought and the Claim ...its in range [more than 30', '15 to 30', 'none', '1 to 7', '8 to 15']
PastNumberOfClaims	: how many times the claims have been made in the past .... ['none', '1', '2 to 4', 'more than 4']
AgeOfVehicle		: Age of Vehicle   ['3 years', '6 years', '7 years', 'more than 7', '5 years', 'new','4 years', '2 years']
AgeOfPolicyHolder	: Age of the Policy Holder... its in range. ['26 to 30', '31 to 35', '41 to 50', '51 to 65', '21 to 25','36 to 40', '16 to 17', 'over 65', '18 to 20']
PoliceReportFiled	: Police Report was filed or not.. ['No', 'Yes']
WitnessPresent		: Any witness to the accident..... ['No', 'Yes']
AgentType		: Agent Type....['External', 'Internal']
NumberOfSuppliments	: ??......['none', 'more than 5', '3 to 5', '1 to 2']
AddressChange-Claim	: ?? .....['1 year', 'no change', '4 to 8 years', '2 to 3 years','under 6 months']
NumberOfCars		: No. of other vehicles under the insurer name, its in range....['3 to 4', '1 vehicle', '2 vehicles', '5 to 8', 'more than 8']
Year			: Year....[1994, 1995, 1996]
BasePolicy		: Base Policy .... ['Liability', 'Collision', 'All Perils']


Description of the Modelling Technique(s):

Description of the Outcomes / Evaluation criteria:

