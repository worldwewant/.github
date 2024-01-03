# White Ribbon Alliance code for NLU and dashboards

This Github account contains all code to train and deploy dashboards.

## Where are the dashboards?

* https://whatwomenwant.whiteribbonalliance.org/
* https://midwivesvoices.whiteribbonalliance.org/
* https://wypw.1point8b.org/ - PMNCH
* https://explore.whiteribbonalliance.org/giz
* https://explore.whiteribbonalliance.org/wwwpakistan
* https://explore.whiteribbonalliance.org/healthwellbeing
* https://admin.whiteribbonalliance.org/ (admin dashboard)

## How to deploy a dashboard?

In each repo there is documentation included for deploying the dashboard to Azure Web Apps or Google App Engine, or you can deploy to any other cloud provider that supports running Node.js and Python.

1. Get your campaign or survey responses and categorize them using [the NLU model](https://github.com/whiteribbonalliance/womenshealthandwellbeing_public).
2. To create a new campaign in the back-end, read the section `CSV file` and `How to create a new campaign` in [the API repo](https://github.com/whiteribbonalliance/dashboard-api). You will need to store your text in Azure or Google Blob Storage
3. Deploy an API server using [the API repo](https://github.com/whiteribbonalliance/dashboard-api)
4. Deploy a front end server using [the front end repo](https://github.com/whiteribbonalliance/dashboard-front)

## 🧑 Who developed this code?

* [Thomas Wood](https://freelancedatascientist.net/) ([Fast Data Science](https://fastdatascience.com))
* [Zairon Jacobs](https://zaironjacobs.com/)
* [Fredy Gamez](https://github.com/orgs/whiteribbonalliance/people/fredygamez) (chatbot)
* [Amol Walunj](https://github.com/Amoldwalunj)

## License

[MIT License](https://raw.githubusercontent.com/whiteribbonalliance/.github/main/LICENSE)
