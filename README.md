💻 Day 3 | 21 Days of SQL Challenge with Indian Data Club
 Sponsored by DPDzero

Today’s challenge reminded me how a simple command can completely change the way we see data.

 The theme was all about ranking and sorting — finding order in the chaos.
Instead of digging through massive datasets, SQL gives us the power to focus only on what truly matters.

🌟 What I Explored Today:
Sorting insights efficiently using ORDER BY
Narrowing results down with LIMIT
Identifying top-performing weeks through data ranking
Realizing how sorting + filtering = sharper decision-making

🧩 Challenge Task:
Find out the top 5 weeks with the highest number of patient refusals across all services.

 A quick and clean query like this helped me extract the pattern instantly 👇

SELECT week, service, patients_refused, patients_request
FROM services_weekly
ORDER BY patients_refused DESC
LIMIT 5;

🧠 Learning Reflection:
What I loved about today’s task is how simple syntax creates powerful insights.

 When data is sorted the right way, the story becomes clearer — and every number starts to make sense.

🚀 Takeaway:
Mastering SQL isn’t just about learning queries — it’s about learning to think in data.

 Every sorted table and every limited result is a step closer to clarity.
Thank you Indian Data Club and DPDzero for keeping this learning journey structured and impactful. 🙌

hashtag#IDCWithSQL hashtag#SQLChallenge hashtag#DataAnalytics hashtag#MySQL hashtag#21DaysOfSQL hashtag#UpskillJourney hashtag#DataDriven hashtag#LearnSQL
