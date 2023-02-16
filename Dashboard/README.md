# analysis of user interaction with Yandex.Zen cards

Technical Task:

1. Business task: analysis of user interaction with Yandex.Zen cards;

2. How often is the dashboard supposed to be used: at least once a week;

3. Who will be the main dashboard user: content analysis managers;

4. Composition of data for the dashboard:
   
    * History of events by card topics (two graphs - absolute numbers and percentages);
    * Breakdown of events by source topics;
    * Table of correspondence of the sources to the topics of the cards;

5. By what parameters should the data be grouped:
    
    * Date and time;
    * Card subject;
    * Source subject;
    * Age group;

6. The nature of the data:

    * Event history by card topics — absolute values broken down by minutes;
    * Breakdown of events by source topics — relative values (% of events);
    * Correspondence of the sources to the topics of the cards - absolute values;
    * Importance: All graphs have equal importance;

7. Data sources for the dashboard: data engineers promised to prepare an aggregating dash_visits table for you. 
    
    * Here is its structure:

record_id — primary key,

item_topic — card subject,

source_topic — the subject of the source,

age_segment — age segment,

dt — date and time,

visits — the number of events.

8. The table is stored in a specially prepared zen database for you;

9. Data update frequency: once a day, at midnight UTC;
