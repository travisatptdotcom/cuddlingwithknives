# Cuddling With Knives submission

*The following is my very best to give an apt timeline and summary of our progress. If any questions arise, please talk to me, Travis.*
*I'll try elaborate wherever necessary.*
---
The following is a submission to the 2021 Water Security Hackathon hosted by the University of Newcastle and Hunter Water. 
The team consisted of five members; Irene L., Matthew H., Michael G., Indy R., and Travis E. 

The goal of this document is to explain and help understand how we approached this challenge and decided to go about solving it.
Overall, it was decided that effective preemptive solutions were best, compared to the already existing solutions; We should worry
about drough before it being upon us, saving water now and having it available later. 



## Notes taken during meetings / Ideas and though processes

---

* **App Name**
    Wise Water?
    Hunter Water?
***Love Water***
* **Sell to other providers?**
* **Summary**
    * *We are solving the education and datas issue around water management.*
    * *We are tackling the 60%+ of water used domestically (the + is for the domestic portion of the 10% “lost” for unspecified reasons)*
    * *We touch on multiple tenets*
    * *“Water efficiency: Supporting water that is managed efficiently, delivering maximum environmental and social benefit at least cost”*
    * *“Water performance: Effective measurement and reporting on water security to our community”*
    * *“Water sustainability: Supporting water that is managed within sustainable limits, delivering whole of water cycle outcomes”*
    * *“Water reliability: Supporting water supplies that are secure, resilient and deliver customer value.”*
* **Problems**
    * *Uncertainty in the future water supplies*
        * Modelling predicts the worst droughts we have seen, i.e. the “Millenium Drought” was conservative to the predictive modelling http://www.bom.gov.au/climate/drought/knowledge-centre/previous-droughts.shtml
    * *Poor Data Analytics*
        * Difficulty in measuring and accounting for water losses
        * Difficulty in correlating losses to the problem source
        * Rudimentary and costly data acquisition methods; cameras are installed to monitor sewers to identify losses, manual inspections of dams and sites
    * *Weak Customer Relationship*
        * Water users and water suppliers are not engaged
        * The relationship does not persist
        * No direct connection to their users
    * *Expensive, High-effort Education*
        * Targeted campaigns “Waterwise” and “I Love Water” only occurring in droughts
        * Difficult and slow distribution
        * Environmental cost
        * Education is reactionary, not proactive
* **Solution**  
    * *A domestic app to record water sources within the home*
        * Easy enough for children to use to identify water sources within the household
        * Information on random water facts when a certain type of water component is identified
        * Prediction of crude water usage based on the number of occupants that use that room and the properties of the
    * *A domestic app to understand household water rating*
        * User rating based on usage
        * Personalised suggestions to improve the usage
        * Keeping up with the Jones’s Target vs Actuals
        * Incentives for implementing change e.g. “Save 5L per week for a month for kids free at the movies”
    * *A domestic app to understand wider water issues and engage with water suppliers*
        * Link to your water company
        * Explore how water works with dams, stormwater, treatment, leakage issues etc.
        * Push notifications for water restrictions, local outages
        * Integration with water accounts
        * Raise issues of leaks at individuals house
    * *A retrofit device that provides greater accuracy of water usage*
        * Vibration or temperature sensor that communicates when a tap is turned on or off
    * *Distribution to a cloud API and sensor feed on your device*
        * Data available to water suppliers
        * Data available within the app to users
        * Data available for potential businesses
* **Implementation**
    * *A single solution app available from the App Store or in browser / Progressive Web App (PWA) form including*
        * The education process of water source identification
        * The motivational incentives for reducing domestic water usage
        * An engagement system between water suppliers and water consumers
    * *Promotion through schools for free retrofit devices for children to fit and explore water interactively in their home*
    * *Hunterwise for highschool?*
* **Road Map**
    * *Future-focused integration of smart technologies*
        * Exploration of higher accuracy sensors during the DA approval integration for
    * *Industry-facing Extension*
        * Industrial sensors
        * Commercial analytics for specialised use cases
    * *Water Supplier Exenstion*
        * Water meter sensors (heavily done before, but important to determine the household usage vs. the usage of each tap, to identify that 10%)
        * Extension to water network sensors in dams & catchments
        * Water visualisation
    * *Pivot to energy consumption*

* **Sensor feasibility**
    * *(water proof) temperature changing i.e. anywhere water flows*
    * *touch sensitivity i.e. on taps*
    * *moisture sensitivity i.e. sprinklers or hoses partnered with reverse extrapolation*
    * *vibration detection i.e. as pipes are running with water they release small vibrations*
    * *sensor examples:*
        * DS18B20 for temp (<$1 each unit per 500 units)
        * esp8266   (<$7 per unit)
        * rechargable batteries, 10+ years  (varying prices, usu. <$1 per unit)
        * potential voltometer (for battery charge checking) (depends on monitary investment)

bom.gov.aubom.gov.au
Previous droughts
Read about previous Australian droughts.


