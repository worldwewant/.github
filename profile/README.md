# World We Want code for NLU and dashboards

This GitHub account contains all code to train and deploy dashboards.

## Where are the dashboards?

* https://whatwomenwant.whiteribbonalliance.org
* https://midwivesvoices.whiteribbonalliance.org
* https://wypw.1point8b.org - PMNCH
* https://explore.whiteribbonalliance.org/giz
* https://explore.whiteribbonalliance.org/wwwpakistan
* https://explore.whiteribbonalliance.org/healthwellbeing
* https://admin.whiteribbonalliance.org (Admin Dashboard)

## Branding guidelines

Colors are RGB, (hex#):

Dark blue: 33, 47, 81 (#212F51)

Med blue: 58,114,149 (#3A7295)

Dk Red: 210, 12, 36 (#D20C24)

Green: 71, 157, 116 (#479D74)

Dk Yellow: 249, 192, 21 (#F9C018)

Gray: 195, 197, 190 (#C3C5BE)
 

## How to deploy a dashboard?

In each repo there is documentation included for deploying the dashboard to Azure Web Apps or Google App Engine, or you
can deploy to any other cloud provider that supports running Node.js and Python.

1. Get your campaign or survey responses and categorize them
   using [the NLU model](https://github.com/whiteribbonalliance/womenshealthandwellbeing_public).
2. To create a new campaign in the back-end, read the section `CSV file` and `How to create a new campaign`
   in [the API repo](https://github.com/whiteribbonalliance/dashboard-api). You will need to store your text in Azure
   Storage or Google Blob Storage.
3. Deploy an API server using [the API repo](https://github.com/whiteribbonalliance/dashboard-api).
4. Deploy a front end server using [the front end repo](https://github.com/whiteribbonalliance/dashboard-front).
5. You can also deploy an admin dashboard for downloading campaigns data
   using [the admin dashboard repo](https://github.com/whiteribbonalliance/dashboard-admin-front).

## 🧑 Who developed this code?

* [Thomas Wood](https://freelancedatascientist.net/) ([Fast Data Science](https://fastdatascience.com))
* [Zairon Jacobs](https://zaironjacobs.com/)
* [Fredy Gamez](https://github.com/orgs/whiteribbonalliance/people/fredygamez) (chatbot)
* [Amol Walunj](https://github.com/Amoldwalunj)

## License

[MIT License](https://raw.githubusercontent.com/whiteribbonalliance/.github/main/LICENSE)
