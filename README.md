# <center>Improve Surgical Efficiency Through Optimizing Surgical Delay Time and Improving Patient care.</center>
## General Insight and Recommendation
### Insights on missing values:

1.) It was noticed that 3 Surgeon name is missing in 3 Procedure

2.) Also no Anaesthetist name in about 112 Procedure
  
3.) Also no Scrub Nurse name in about 94 Procedure

4.) About 5 Procedures was not scheduled

### Insight from analysis

Average Delay Time: 67.89 minutes

Averag time spent for procedures: 136.72 minutes
    
It was noiced that the major cause of delay are:
    
1.) The Previous Surgery is one of the major cause of delay with a total of 7514 minutes i.e  125 hours 3 minutes, and most of the procedures about 56 where delayed by previous surgery.
    
2.) The Patients coming late to scheduled procedure also contribue to the delas second to delay caused by previous surgery, with total delay time of 3674.0 i.e 61 hours and 24 minutes, which spanned through 26 procedure.
    
3.) Also most attime the surgeons are not ready for the procedure which cause delay of about 1552.0 minutes in total, i.e 25 hours and 86 minutes in total, which spanned through 13 procedures.

#### Top 3 surgeons and procedure thas has the most delay with highest time.
<b>1.)Surgeon:                        DR DANIEL</b>

Procedure:                    CIRCUMCISION

Reason for Delay:       SURGEON NOT READY

Delayed_time_minutes:                928.0 minutes



<b>2.)Surgeon:                        DR ASHRAF</b>

Procedure:                    PLASMA RICH PLATELET INJECTION

Reason for Delay:       PATIENT CAME LATE

Delayed_time_minutes:                864.0 minutes



<b>3.)Surgeon:                        DR EKWE</b>

Procedure:                    NERVE ROOT AND CUDAL EPIDURAL INJECTION

Reason for Delay:       PATIENT CAME LATE

Delayed_time_minutes:                845.0 minutes


#### Analyze Delays by Anaesthetist
Anaesthetist with Most Delay: ('UGHEOKE', 'PREVIOUS SURGERY DELAYED') with 1185.00 minutes

<b>Top 3</b>
Anaesthetist,     Reason for Delay, minutes 

UGHEOKE,          PREVIOUS SURGERY DELAYED,    1185.0 minutes

SOLANKE,          PREVIOUS SURGERY DELAYED,     785.0 minutes

UGHEOKE/OLULODE,  SCHEDULED SAME DAY,           730.0 minutes


#### Analyze Delays by Scrub Nurse

<b>Top 3</b>
Scrub Nurse    Reason for Delay, Time

NURSE MARYANN,  PREVIOUS SURGERY DELAYED,                                                 1540.0 minutes

NURSE GONYA,    PREVIOUS SURGERY DELAYED,                                                 1424.0 minutes

NURSE GRACE,    PREVIOUS SURGERY DELAYED,                                                 1205.0 minutes

NURSE OGECHI,   SCHEDULED TIME NOT FOLLOWED AS SURGEON HAD HIS OWN LIST THAT WAS USED,     986.0 minutes
                   
NURSE OGECHI,   PREVIOUS SURGERY DELAYED                                                  928.0 minutes



#### Trend Analysis:

Most delays are between 1 to 2 hours


#### General Reasons for Delay Across Roles:

##### Surgeon: 

Delayed by Previous Surgery and Patience coming Late are the major Reason given by Surgeon, DR ADEDAPO had about 13 procedure missed because of delay from previous surgery, follow by DR AYENI 5 surgeries delay, reason that patient came late.

##### Anaesthetists

Major Delays given by Anaesthetists came from delayed by previous surgery, and others from surgeon not being ready, Anaesthetist AKINMOLA reasons for delay in 3 surgery was that SCHEDULED TIME NOT FOLLOWED AS SURGEON HAD HIS OWN LIST THAT WAS USED

##### Scrub Nurse

Delaed by the previous surgery, anaesthetist, surgeon delayed and not ready, and emergency surgery are the most reason given by Scrub Nurse

### Recommendation

1. Solving Delay for a surgery due to a delay from the previous surger we can do this:
    
    * Schedule buffer times between surgeries to accommodate potential overruns. This extra time can absorb delays from previous procedures without affecting the start time of subsequent surgeries. 
    * Understanding the data to determine the average time spent for different types of surgeries. Incorporate this data to create buffers that vary based on the complexity and expected duration of each surgery.
    * To Improve scheduling, advanced predictive analytics can be used to accurately estimate surgery durations. Machine learning algorithms can analyze historical surgery data, considering factors like the surgeon, type of procedure, patient condition, and time of day to predict more realistic surgery times.
    * Continuously review surgical schedules and outcomes to identify patterns in delays. Use this data to refine scheduling practices and protocols.
    * Set up a regular feedback loop where delays are analyzed, and findings are communicated to the surgical and administrative teams. Adjust scheduling policies based on these insights.
    * Optimize pre-surgery processes such as patient transfer and operating room turnover to reduce the time between surgeries.
    * Conduct time-motion studies to identify inefficiencies in pre-surgery activities and implement process improvements such as quicker room turnover protocols and faster patient transport.

2. Solving Delay for a surgery caused by surgeon, Anaesthetists, Scrub Nurse  we can do this:

    * Encourage staffs to be mindful of their time and work efficiently. Hold regular debriefings to review delays and discuss ways to improve time management during surgeries.
    * Allow surgeons some flexibility in scheduling their surgeries. For instance, they might be able to adjust their schedule on the day of surgery based on the progress of earlier cases.


3. Solving Delay for a surgery caused by Patient:

     * Implement a system that sends automated reminders to patients about their surgery time, including instructions on when to arrive at the hospital. Reminders can be sent via SMS, phone calls, or email.
     * Pre-Surgery Instructions: Provide clear and detailed instructions on what patients need to do before the surgery, including the importance of arriving on time.
     * Personalized Communication: Tailor reminders to each patient’s needs, considering factors like travel time to the hospital.
     * Patient can be charge an addition fee when delay is caused by them, because time is of essence.
