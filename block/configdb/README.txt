### timeOffset.csv ###

This file contains the time offset 'TimeOffset_s' relative to UTC that 
exists at a particular time stamp 'Timestamp_yyyymmddTHHMMSS'. The
time offset' value, in seconds, is subtracted from the timestamp to
obtain the UTC time stamp that will be used for syncing audio and
navigation data.

- TimeOffset_s: time offset, in seconds, referred to UTC for a given local 
  time 'Timestamp_yyyymmddTHHMMSS'.
- 'Timestamp_yyyymmddTHHMMSS': local timestamp with associated time offset.
  It must be expressed with format yyyymmddTHHMMSS, where 'y','m','d','H',
  'M','S' represent digits of the year, month, day, hour, minute and second,
  and 'T' is a delimiter indicating the start of the time string.


