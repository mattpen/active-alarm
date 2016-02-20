# active-alarm
CS Learning for Kids - AppInventor Projector


##For Thursday:
+ Store alarm information in DB - Matt
+ Check location and calculate distance - Abhijit
+ Check time, start audio - Anna


##Alarm:
+ Create and save to storage a list of alarm days and times.
+ When the clock senses that one of the alarm date/times has been reached, start the audio file.
+ Trigger alarm off only when the absolute difference in geolocation (distance) is beyond a threshold
+ If time permits. use text to speech and speech recognition modules to toggle alarm. (It would be interesting if instead of alarm audio, it uses web news api to talk about “headlines of the day” as the alarm audio)
+ Have multiple modes of difficult either based on increasing distance or bar code scanning/ gyro sensor



Alarm Object:
`( name (unique ID), Day of week, time of day, audio file, stop conditions)`

Stop Conditions Object:
    May be extended later, for now just a distance to be met. Type will always be = distance, value = distance in miles (decimal).
    `( name (unique ID), type, value )`
