# ConfrenceApp
Confrence1:
	Track1:
		Session: 1
			Talk1
			Talk2
		Session 2
			Talk3
	Track2:
	Track3:
	
	Select Your confrence: confrence
	Upload the csv for topics: csv
  
  Confrence => Tacks (n) => Session (n) => tasks (n) 

Confrence: {
startdate:
enddate:
creator:
title:
Tracks:  [] Track
}

Track: {
title:
category:
sessions: [] session
}

Session: {
title:
category: Morning/Evening/Afternoon
StartTime:
EndTime:
Talks: [] talk
}

Talk: {
type: regular/lightining,
duration: in minute
max time: in minute
author: talk person
topic: 
}

LunchBreak (Dfeault Session)
Networking (Dfeault Session)

CSV:

type, duration, author, topic
