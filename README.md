<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=3600&pause=900&color=2F81F7&center=true&vCenter=true&width=760&lines=Supply+Chain+Analytics+%7C+Python+%7C+SQL+%7C+Inventory+and+Transport;Most+operations+metrics+answer+a+question+nobody+asked" alt="Supply chain analytics, Python, SQL, inventory and transport" />
</p>

## 👋 hey, I'm Uday

Four years in supply chain analytics, starting at Mahindra Logistics on third party logistics
in India and now at Cargill on agribusiness in the US, with a master's from the University of
Bridgeport.

The thing I keep running into is not a model that is wrong. It is a number that is answering a
different question from the one it is read as. A safety stock formula solves for the share of
replenishment cycles that survive, and the review deck reports the share of units served. A
carrier scorecard starts counting at ship confirm, so a delay that happened before it is not
measured imprecisely, it is not measured. A forecast backtested on sales is graded against
availability on every day the shelf was empty.

None of those are precision problems that more data fixes. They are the metric and the
objective being different quantities, and the gap does not show up as an error bar.

The repositories below are small and each one takes a single case of that. They generate data
with the answer planted, so the claim can be graded rather than argued, and every figure in
every README is read from a run and re-checked by CI against the prose that quotes it. Where
a measurement refuted what I expected, which happened in four of the seven, the refutation is
in the repository rather than removed from it.

## 🛠 what I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat&logo=ruff&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat&logo=sap&logoColor=white)

## 📌 what is in the repositories

Each one is a measurement of a metric that is read as answering something it does not answer.
They are ordered by how much of the gap is structural rather than a matter of degree.

**[transit-time-attribution](https://github.com/GITHUB_USERNAME/transit-time-attribution)** ·
A carrier scorecard's window opens at ship confirm, so 73.0% of late deliveries here have a
cause it cannot see, and it is right 92.6% of the time about the ones it does flag. Reports
whether a named cause is true of the shipment at all, because the planted label records one
of several true answers.

**[service-level-gap](https://github.com/GITHUB_USERNAME/service-level-gap)** ·
Cycle service level and fill rate are 16.4 points apart on this demand, and a policy solved
for 95% cycle service delivers 81.5% because the formula ignores undershoot of the reorder
point. The normal assumption costs 0.26 points; the undershoot costs 12.1.

**[censored-demand-backtest](https://github.com/GITHUB_USERNAME/censored-demand-backtest)** ·
A stockout replaces demand with your own availability, so a backtest on sales prefers the
forecaster that ignores censoring at every fill rate up to 92.8%, and rejects the correction
that is right. The two agree again at 97.5% fill, which is where the finding stops.

**[grain-reconciler](https://github.com/GITHUB_USERNAME/grain-reconciler)** ·
Shrink is computed from a moisture probe rather than weighed, so the loss line is a residual.
Changing only the contract's formula moves the reported loss by a factor of 5.9, and the
reconciliation reports created grain on 16.1% of loads.

**[abc-xyz-churn](https://github.com/GITHUB_USERNAME/abc-xyz-churn)** ·
Reclassify an assortment quarterly and 805 items change class while 108 changed tier. On an
assortment where no item ever changes tier it still produces 770 changes, and a two quarter
hold removes 78% of them at a cost the table reports beside the benefit.

**[forecast-skill-vs-mix](https://github.com/GITHUB_USERNAME/forecast-skill-vs-mix)** ·
A portfolio WMAPE is a weighted average, so a change in it cannot be attributed between
forecasting skill and mix shift without a convention. A 2.86 point improvement is 41% skill
under one convention and between 33% and 48% across four.

**[demand-cleaning-cost](https://github.com/GITHUB_USERNAME/demand-cleaning-cost)** ·
A promotion and a mis keyed quantity are the same size, so under the rule that catches the
most errors, 85.5% of what it removes is real demand. Set out to show cleaning moves a
forecast more than the model does; measured fairly it does not, and the repository says so.

## 📬 connect

![Email](https://img.shields.io/badge/Email-PLACEHOLDER--EMAIL-D14836?style=flat&logo=gmail&logoColor=white)
![LinkedIn](https://img.shields.io/badge/LinkedIn-PLACEHOLDER--PROFILE-0A66C2?style=flat&logo=linkedin&logoColor=white)

---

<sub>"All models are wrong, but some are useful." The harder case is a model that is right and
is answering a different question.</sub>
