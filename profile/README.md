# World We Want code for NLU and dashboards

This GitHub account contains all code to train and deploy dashboards for the World We Want Project.

More info: https://worldwewantproject.com

## Where are the dashboards?

* https://exchange.worldwewantproject.org/en
* https://wypw.1point8b.org - PMNCH
* https://admin.worldwewantproject.org (Admin Dashboard)


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


## Branding guidelines


Colors are RGB, (hex#):

### Dark blue

![212f51](https://raw.githubusercontent.com/worldwewant/.github/main/colours/212f51.svg)
```
212f51
```
```
rgb(33, 47, 81)
```

### Med blue

![3a7295](https://raw.githubusercontent.com/worldwewant/.github/main/colours/3a7295.svg)
```
3a7295
```
```
rgb(58, 114, 149)
```

### Dk Red

![d20c24](https://raw.githubusercontent.com/worldwewant/.github/main/colours/d20c24.svg)
```
d20c24
```
```
rgb(210, 12, 36)
```


### Green

![479d74](https://raw.githubusercontent.com/worldwewant/.github/main/colours/479d74.svg)
```
479d74
```
```
rgb(71, 157, 116)
```

### Dk Yellow

![f9c018](https://raw.githubusercontent.com/worldwewant/.github/main/colours/f9c018.svg)
```
f9c018
```
```
rgb(249, 192, 24)
```

### Gray

![c3c5be](https://raw.githubusercontent.com/worldwewant/.github/main/colours/c3c5be.svg)
```
c3c5be
```
```
rgb(195, 197, 190)
```

### Fonts

Halyard Display on the dev site at the moment for all heads and body, but we often use Proxima Nova family, so may shift to that. Both are similar, clean sans fonts.


## License

[MIT License](https://raw.githubusercontent.com/worldwewant/.github/main/LICENSE)
