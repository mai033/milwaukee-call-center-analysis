# Milwaukee Call Center Analysis

This notebook analyzes call center data for the City of Milwaukee as part of a senior data scientist assignment.

I loaded and explored both the historical and current datasets. I converted the date fields so I could look at trends over time and calculated how long each case took to get resolved.

I then created charts to look at:

- How call volume changed over time  
- The most common types of service requests  
- The most frequent case closure reasons  
- How long it took to close each case  

1. Call volume was much higher during 2020, with some days getting more than 1,750 calls. After that, the number of calls dropped and stayed lower from late 2020 through 2025. There were a few spikes in 2023, with some days reaching over 500 calls, but those increases were short-lived and quickly dropped off again. This big change might be due to updates in the system, new policies, or shifts in how the city handled requests after COVID.

2. The most common issue reported was:  
Brush Pickup Request, Less than 2 Cubic Yards (April–November), followed by:  
- Parking Violations Information
- Street Light Out    
- Missed Collections: Garbage  
- Potholes  
- Missed Collections: Recycling

These show that residents mostly call about waste pickup, parking questions, and street maintenance.

3. The most common case closure reason was:  
“Is night parking enforced?” — this shows that many people are unsure about city rules.  
Other common closure notes like “Aware of size limits”, “Exception entered”, and “Caller request” suggest that notes are being typed in freely, which makes the data harder to analyze.

4. Over 57,000 cases were closed within 35 hours, which shows that the team is doing a good job of responding quickly. But there are also some cases that take several days or even weeks to close. These might be more complicated issues or ones that need help from different departments.

---

### Recommendations
- Since brush pickup requests spike from April to November, it would help to plan ahead for more staff or use automation during those months.

- Add clearer information on the city website and in seasonal updates about things people often ask about, like night parking and brush pickup rules. This could reduce the number of calls.

- Use dropdown menus instead of free typing for closure reasons. This would help keep the data clean and easier to track.

- Take a closer look at cases that take more than 72 hours to close. This might help find delays or areas where the process could be improved.
