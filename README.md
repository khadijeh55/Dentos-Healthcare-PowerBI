<img width="1198" height="682" alt="image" src="https://github.com/user-attachments/assets/b987fc3c-c167-4258-a078-4ce016c41f99" />
<img width="888" height="625" alt="image" src="https://github.com/user-attachments/assets/e5992021-3cea-4984-9d9e-18f24a73eacb" />

# Dentos Healthcare: Appointment Analytics Project

## Comprehensive Executive Summary

### 1. Overall Performance Overview
* The clinic successfully managed a total baseline of 96K appointments, achieving a solid patient attendance rate of 80.13% (77K successful visits).
* The overall No-Show Rate stands at 19.87% (19K missed appointments), which serves as our primary operational metric for clinic optimization.

### 2. Key Insights & Patient Behavioral Trends
* **The Early-Morning No-Show Peak:** A critical operational pattern was discovered in the Scheduled Hour Trend. There is a sharp spike in patient absenteeism in the early hours of the morning, peaking near 35%–40% right before 10:00 AM. Conversely, appointments scheduled after 10:00 AM exhibit a remarkably stable and low no-show rate (under 20%) throughout the rest of the day.
* **Lead-Time & Wait Duration Impact:** Our advanced analysis reveals a powerful, direct correlation between lead time (the duration between the booking date and the actual appointment date) and patient absenteeism. Patients with "Same Day" bookings demonstrate an exceptional attendance record, with a no-show rate of only ~5%. However, as the waiting period expands, the no-show rate climbs steadily to 17% for 1–3 days, 25% for 4–7 days, and reaches a staggering peak of over 32% for appointments booked more than 2 weeks in advance. The overall Average Waiting Days for the clinic stands at 9.93 days.
* **Medical Profiles Impact:** The No-Show Rate by Medical Condition chart indicates that the vast majority of the clinic's patient baseline does not suffer from hypertension. More importantly, the proportion of missed appointments remains relatively identical between patients with and without pre-existing medical conditions, indicating that health status is not a primary driver of absenteeism.

### 3. Strategic Action Plan & Recommendations
* **Targeted Reminder Campaigns:** Implement an automated SMS or phone-call confirmation campaign specifically targeted at patients who book slots between 8:00 AM and 10:00 AM, executed exactly 24 hours prior to the appointment.
* **Mitigating Long Lead-Time Risks:** Since appointments booked more than 2 weeks in advance have a 32% chance of failure, the clinic should consider applying strategic overbooking rules exclusively for these slots, or offer a "short-notice booking incentive" to fill empty windows.
* **Socioeconomic & Regional Deep-Dive:** Leverage the newly integrated "Neighbourhood" and "Scholarship" slicers to filter the active dashboard and pinpoint specific low-income areas or remote districts that display above-average no-show rates. This allows management to allocate transport assistance or localized social support where it is needed most.
