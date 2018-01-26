# crypto-tuning

# strategy
```python
params = {
  "beginHour",
  "endHour",
  "high_rate",
  "low_rate"
}
```

# Roadmap
* [x] load 2017 data (hourly)
* [x] fetch last data from the web
* [x] process increase percentages by hour
* [x] process decrease percentages by hour
* [x] process potential gain by strategy
* [x] add columns : nbWins & nbLoses & ratio
* [x] plot curve day by day
* [ ] how to define next week hyperparameters ?
* [ ] add a workflow :
  * run hyper_tuning for last 2 weeks + current one
  * show 15 best configurations for these weeks
  * select one configuration, for each week, show gains win/lost ratio
