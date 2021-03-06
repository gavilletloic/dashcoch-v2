# Dashcoch-v2

Version two of the [dashcoch project](https://github.com/daenuprobst/dashcoch) visualizing Swiss COVID-19 data.

## Development

This project required no backend. Feel free to fork. PRs are welcome. I used Pythons simple web server to develop:

```bash
python -m http.server
```

## TODO

- [ ] Disply no data available in age pyramid for hospitalizations
- [ ] Add message that recent data might be incomplete
- [ ] Refactoring: `app.js` is a mess and there are some ugly globals
- [ ] Check whether it makes sense to add cantonal mobility data (small cantons don't really have any)
- [ ] Update summary depending on selected date
- [ ] Sort labels / tooltip by value
- [ ] Plot stringency vs. change in GDP
- [x] Show all cantonal labels in canton heatmap
- [ ] Add moving average curve to date bar charts
- [ ] Add positivity rate to summaries
- [ ] Sum of excess mortality
- [ ] Add all sex to age/sex heatmap
- [ ] Add trails (past n days) in scatters
- [ ] Bring back option for log axis
- [x] Show "No Data" message for age when selecting hospitalizations
- [x] Add canton labels to map

## More to follow

Stay tuned.
