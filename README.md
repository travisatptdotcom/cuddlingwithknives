# Cuddling With Knives submission

*The following is my very best to give an apt timeline and summary of our progress. If any questions arise, please talk to me, Travis.*
*I'll try elaborate wherever necessary.*
---
The following is a submission to the 2021 Water Security Hackathon hosted by the University of Newcastle and Hunter Water. 
The team consisted of five members; Irene L., Matthew H., Michael G., Indy R., and Travis E. 

The goal of this document is to explain and help understand how we approached this challenge and decided to go about solving it.
Overall, it was decided that effective education on preemptive solutions were best, compared to the already existing solutions; 
We should worry about drought before it being upon us, saving water now and having it available later.

Effective education can be difficult, especially in regards to something not frequently thought over such as water, so practical 
demonstration and encouragement through reward are methods we found to make the most sense, and have the highest potential effect 
on all that use our solution. This includes monitary reward (coupons, showing money saved, insentives similar to the Dine & Discover 
vouchers), visualistion of water and money saved (see the [Ubuntu donations page, and how it shows what your donation can afford](https://ubuntu.com/download/desktop/thank-you?version=20.04.3&architecture=amd64)), and your own impact on the economical aspect of water sustainability (such as [Hunter Water's Water Usage Calculator](https://waterusage.hunterwater.com.au/)). The above points are designed to raise the margins of people who become educated and more waterwise through 
the useage of our solution.

Integration the above points into **one functional app**, partnered with cost-and-energy-efficient household sensors and interaction with water providers 
and users of our solution, seemed to make the most sense. One app in which you can seek help for saving water, monitor your actual, real 
time water use, see the water useage around you and reflect on what you've done by saving / wasting water makes the access to and feasability of this simple
for everyone, the only ancilaree action needed is dependant on the overhead of the project; a decision for Hunter Water is how to help
people interact with their water useage, such as by providing (access to) sensors which can be used to monitor water as a cost 
effective and long lasting solution. 

Such sensors have been researched by our team, costing on average less than $9 per unit. Compared to the water saved and lack of
investment in water purification through said saved water, this single ramshackle example is a perfect example of how our solution 
proves its use when partnered with Hunter Water.

This app, coined **Love Water** by our team, is approachable, to prove it we have provided a link during our presentation to our [mockup app](https://personal-0wc4x8fv.outsystemscloud.com/LoveWater/)
showing that anyone can use it and understand it. This approachability is again increasing the margins of people affected and educated 
on waterwise solutions 


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


