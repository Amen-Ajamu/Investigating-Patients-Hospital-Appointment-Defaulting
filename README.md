# Investigating-Patients-Hospital-Appointment-Defaulting
### by Amen T. Ajamu
## Dataset Description 

This dataset pulled from [kaggle.com](https://www.kaggle.com/joniarroba/noshowappointments) collects information from 110,527 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. Considering the 'no_show' column as the dependent variable, the 'appointment_id' and 'patient_id' as identifiers, the other columns list out the attributes of each one of the patients.


Take note that in the 'no_show' column 'yes' means they did not show up, while 'no' means they actually did show up.

## Summary of Findings

A larger proportion of the patients showed up for their appointment. The majority of the patients who showed up are female and half of these patients are aged 18 to 55. However, it may be impossible to draw any concrete statistical significance from this because it is exactly reflective of what is found in the total dataset. Any statistical work of significance will require sampling.

As seen in the "time_lag" column, a number of values were negative. The only logical explanation I could come up with about that is that some of the patients booked for an appointment days or hours after they were normally supposed to or that there is a problem with the dataset.

It is also shown in the scatter plots that being advanced in age increased the number of disease conditons the patients had. Those who had none of alcholism, diabetes and hypertension were younger than 20 years of age.

It is interesting to note that while the age distribution for the patients who did not show up for their appointment is more skewed to the right than those who did show up, there is similarity in the pattern of distribution. In both category of patients the highest proportion are patients aged between 0 and 10. This may be due to two reasons in my opinion:

>It is reflective of the age distribution in the general data set. As such, sampling will be very central to making a concrete statistical inference from the dataset. 
       
>That there is infact a problem with the dataset as the age value '0' makes up the most of the chunk of that dataset. Unfortunately there was no information of the reason why the patients booked the appointment to give one a justification for dropping the datasets with age value = 0
