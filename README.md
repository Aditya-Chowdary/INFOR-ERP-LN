# INFOR-ERP-LN 
  (ENTERPRISE RESOURCE PLANNING)

ERP

E – Enterprise or business
R – materials, machinery and manpower need to build a PRODUCT
P – efficient of using resources
it is a planning structure of a company resources 
TRITON is a FIRST VERSION
Logistics – transportation of supplies, storage, and distribution
User interface – 1.web based
                       2.worktop
                       3.BECS
                       4.CUI
SUPER USER – He can check each and everything
NORMAL USER – He will have restrictions
VERSIONS:
TRITON > BAAN > SSA GLOBAL > INFOR > KOCH
-	Packages
-	Distribution
-	Sales
-	Purchase
SESSION NAME “TDSLS4101M000”
Where TD – package - (Triton Distribution)
          SLS – module 
          4101 - session code
           M - session type
           000 – company number

-	ION – Intelligent open network
-	INFOR OS – operating services
-	BI TOOLS – business tools
-	PLC – product life cycle tool
-	AWS – amazon web services
-	WH – warehouse
-	TF – Triton finance
TOOLS are the base layer of ERP
ERP LN an OS independent
B shell – productive layer bridge between user and system
BISAM / TBASE – Database created for Triton
Database – tables, logs
ERRORS: while we are using ERP we will get some errors like
-	Error 606: Referential does not exist
-	Error 512: domain or structure mismatch between DICT & DATABASE
BSE – BAAN SOFTWARE ENVIRONMENT

-	API (application interface)
-	LIB – libraries 
-	JAVA (tomcat)
-	SHLIB 
-	BIN – user profiles and database things
-	APPLICATION
-	DICT – it is a key thing which identify the data it is called as data dictionary (table information associated with company number)
-	TOOLS (base layer)

- Upgrading Bshell it is also called as porting set it is only one time process
                                                                                                                                

                              before upgrading porting set backup 5 folders                       
                                                                                       


VERSION RELEASE & CONTROL (VRC):
                                           
                                                                                                                                                                                        









Collection of modules – (packages)
ERROR: package combination not found /equal
-	1st goes to the production checks the package if not goes to the own/customization checks if not then update checks there also if not goes to base
-	Derives from next layer.

TOOLS FOLDER – DD (data dictionary)/TT6.1 (triton tools)/TL6.1 (advanced tools)
APPLICATION FOLDER – F/M/I/P/O
Session: Form/Object/Info/Programme/Menu
MARKET TO CASH
ORDER TO CASH
PROCURE TO PAY
MAKE TO STOCK


MARKET TO CASH:
Market to cash is a cycle where sales representers goes to the market to get orders from the customers, when the customer interested in the product, sales representative gives a quotation to a customer and the customer will gives a purchase order.

ORDER TO CASH:
When a company got an order they check for stock availability, if stock is not available in bulk warehouse ,they check for raw materials to build product is enough or not if it is not enough they will inform to purchase department, then purchase department goes to a vendor for a procurement of raw material and gives a purchase order to a vendor then the inspection department checks the quality and quantity of material and on time delivery or not, if it is passed in inspection it will forwarded to manufacturing department and the product start building after completion, inspection team again checks the product for quality if it is passed there also it goes to the bulk warehouse from there to customer, if the product not qualified quality test that product goes to the scrap warehouse and scrapped it, and they store the extracted material in raw material warehouse and reuse it. If raw materials are not passed in inspection, materials will dump into quarantine warehouse, and they inform to purchase department and the purchase department goes to the vendor and asks about the quality of raw materials if the vendor accepts for replace, they replace it otherwise they send it to scrap warehouse to sell or trash.                   

PROCURE TO PAY:
if there is a not enough raw materials to build a product then the purchase department goes to vendor for goods and gives a purchase order, based on payment terms they pay to vendors.

MAKE TO STOCK:
Based on the previous forecast orders and demand forecast and sales history they produce products and store it.
COMPANIES

1 company will have only one package
A group can have set of companies
There are FINANCE companies and LOGISTICS companies
SINGLE FINANCE AND SINGLE LOGISTICS
         900(a single COMPANY)
-	It is the only one company that doesn’t have any sub companies, that company will handle the all the details and plannings regarding production.
SINGLE FINANCE AND MULTI LOGISTICS
       (900 – 100/200/300)
-	Main office will give’s fund that are needed to build a product and sales done in those subbranches
MULTI FINANCE AND SINGLE LOGISTICS
      (100/200/300 – 900)
-	Manufacturing may done in single company but transactions and sales are done in sub companies
MULTI FINANCE AND MULTI LOGISTICS
-	In this model all branches and groups are interlinked 
-	Intercompany transfers done
-	Internal transfers of products and services is done
ITEMS
-	Raw materials and finished goods are called items
STANDARD ITEMS      &     CUSTOMIZED ITEMS
Produced in bulk                 customizes the product 
And sales                               according to customer order and sales
Every material will have its ITEM CODE
ITEM COSTING 
-	Raw material
-	Cost calculation – checks all expenses to build per a product ITEM COST
-	BOM (Bill of material) – the materials used in a product comes to BOM
-	Routing – ways involved in completion of task to build a product, time taken to build a product and how many products had build in machine in given operational time
After item costing, they club related items as a group it is called as ITEM CLASSIFICATION
BUSINESS PARTNERS
Vendors and customers are the partners of a company
Name
Billing address – where we get money for our delivered product
Shipping address – where the product to be shipped
Contact details
PRICE BOOK – in price books there is a complete info about product and product no, if they want to order they can understand terms and conditions which are helpful to easy for transactions. Price book changes by ITEM COSTING before changing prices they setup an expiry date for price after based on demand and market condition they increase 
-	Delivery terms and Payment terms are there in a SALES ORDER
-	In SALES ORDER on header part there is a complete information about customer
-	And in line level there is information about the product and prize




FLOW CHART FOR REQUEST FOR QUOTATION                                                                                                                                                       












Master data 

MASTERDATA
CRM
SALES
PROJECT
PLANNING
MANUFACTURING
PROCUREMENT
WAREHOUSING
FREIGHT (DELIVERY)
SERVICE (ISSUES)
QUALITY
FINANCIALS
INVOICING
UNITS
-	materials count based on unit of measure
-	Sets of units we will add units into set of units based on their standard measurement
BUSINESS PARTNERS addresses
-	Name
-	Street
-	Landmark
-	Locality
-	City
-	Zip code
-	 State
-	Country
-	Ph numbs
-	E mail

Based on zip code tax sessions goes
Every state has its own tax
And tax based on revenue of their local municipality tax will assign
Tax will assign to invoice address only based on their tax interests
Based on county revenue decision they change tax monthly
Tax session modules set for only one time
GEO CODE – (Geographical code)

PROCURE TO PAY
We need a material to build a product if we lack of material we go for a procurement



















PURCHASE ORDERS
BLANKET PO
If we know the requirements of our required raw materials, we will release a blanket po for a certain time duration instead of releasing monthly we will say the vendor that EX - we need every month this much of qty for 1 year 
We will prefer for a BLANKET PO we cannot close this po until the time duration is completed
SERVICE PO
If we need a service people in our company, we will take them based on time and money basis by using service po it is a temporary alignment
MACHINERY PO
If we need a machine, we release a machinery po, we use machine in our company and pay for it as a rental
SUBCONTRACTING PO
Allocating our work to somebody else to complete by releasing a subcontracting po
VENDOR MANAGING WAREHOUSE PO
The vendor will put the material in our vendor managed warehouse if we use that material for production, we will inform to finance department to bill for it (partial invoicing)

OEM - Original equipment manufactured parts



MASTER DATA

-	BUSINESS PARTNERS

       we need to first maintain the business partners details 
-	Contact details
-	Addresses
After that we need to create a business partner types by filling the 






CREDICT CHECK for business partners
Based on credit check they give u a rating
Based on customer credit (there is a blocking the business partners)
CREDIT NOTE – credit note is released when u payed early before the payment terms time
EDI – (Electronic data interchange)
850 – converts PO > sales order (it has blockings)
997 – confirmation
855 – order acknowledgment
856 – shipping (Advance shipping notice)
810 – Invoice generation

DRAFT INVOICE – when we pay amount before the delivery
PARTIAL INVOICE – Partial deliveries





UNITS




UNITS – units define the units of measure
-	Units are grouped by unit sets to items or item groups
-	Base units must be defined in the parameters for a company
-	Conversion factors determine unit to unit equivalents

ENTERPRISE UNIT

Enterprise unit is a bridge between finance and logistic company
Financial independent part of our organisation
DEPARTMENTS

-	Sales office
-	Purchase office
-	Work center 
-	Service department
-	Shipping office
-	Accounting office

SITES

Sites is nothing but a place or location of our company
-	Site will have multiple warehouses
Based on site wise standard item cost calculation is happened
Item is defined by site location
INTERNAL SITE
That is related with our company location (location may differ)
EXTERNAL SITE
External people or companies performing activities FOR OUR COMPANY
ADMINISTRATIVE SITE
They do instructions from there to other sites
They will not do any financial activities



STRUCTURE OF COMMON DATA











COMMON DATA PACKAGE
-	PARAMETERS
-	TABLES

NUMBER GROUP
-	Used to define information specific to a type of document, order, or other logical numbering sequence
-	Number groups, series codes and first free numbers provide order and number generation management

ENTITIES
-	Departments
-	Warehouses
-	Business partners
-	Projects
-	Entities are linked to an enterprise unit to coordinate the financial transactions originated in that entity

WAREHOUSE

An entity or a department used to store purchased or manufactured goods
WAREHOUSE TYPES
-	Normal
-	Shop floor
-	Project
-	Service
-	Service customer owned
-	Service reject
-	Consignment (owned)
-	Consignment (not owned)

DEPARTMENTS
 
-	Sales office
-	Purchase office
-	Work center  
-	Service department
-	Shipping office
-	Accounting office
-	calculation office 
ITEM TYPES

PURCHASED – The items that we purchased from supplier 

MANFACTURED – the item that built by us it consists of (bill of material) we can procure the item also

COST – intangible items electrical charges and other charges machinery charges while we are taking machinery and building because we need to maintain so they make as 
cost item based on all expenses cost calculation differs by item classification

GENERIC – different categories of product based on their requirements they made it differ from product to product like colours like bike colours

SERVICE – warranty about the product and service

SUBCONTRACTED – if our work was done some other people on money basis 

LIST – it consists of belonging items example (TOOL KIT) based on related items we make a list of a product

ENGINEERING MODULE – test and compare with another product

ITEM GROUPS (PRODUCT TYPE, PRODUCT CLASS)

ITEMS SUBENTITIES 

(ORDERING, COSTING, WAREHOUSING)

ITEM PURCHASE – All details related to the purchase activities

ITEM SALES – All activities related to sales

ITEM PRODUCTION – All details of manufacturing and processes involved in it

ITEM ORDERING – All related to amount of quantity of ordering

ITEM COSTING – after all sub entities we estimate a price of product in our LN based on all expenses 

ITEM PLANNING – This will help us to plan a production on which time we need to delivery that order

ITEM WAREHOUSING – This will do multiple tasks like it will decide which product is to (outbound method) like first in and first out

ITEM PROJECT – it has 2 types (existence manufacturing project)

ITEM QUALITY – quality assurance

ITEM SERVICE – warranty of a product and service of a product and how to claim the warranty

ITEM FREIGHT – Transportation and delivery details

ITEM LOCALIZATION
