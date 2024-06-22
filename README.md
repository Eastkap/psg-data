# About Dataset

Data is the result of scraping PSG's marketplace called Ticketplace. For now, only the 2023 - 2024 season is available but I plan to release updates to it. The data was collected to analyze the ticket prices of PSG's matches and to predict the ticket prices for future matches. I also would like to hear from you if you have any ideas on how to use this data and your results. I am open to collaborations.

## About Data collection methodology

Data was collected through Node.js. I cannot provide any more information but in case you want to know more about the methodology, feel free to contact me. If you have inputs on how to improve it, I would be happy to hear them. I also am only releasing a csv but maybe json or sql would be better. I am open to suggestions.

### Description of the data

Data structure is quite simple. There are 4 columns: ts, fixture, category, quantity and price. The ts column is the timestamp of the data collection. The fixture column is the match that the ticket is for. The category column is the category of the ticket. The quantity column is the number of tickets available for that category. The price column is the price of the ticket.

```csv
ts;fixture;category;quantity;price
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 16;1;67,00 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 5;1;136,00 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 13;1;78,99 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 12;1;75,00 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 14;1;69,00 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 9;1;98,00 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 17;1;59,99 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 6;1;125,00 €
1692806160841,match-foot-masculin-paris-vs-lens-1;CATEGORIE 7;1;115,00 €
```

## Authors

* **Jacobo Sanchez** - *Initial work* - [eastkap](https://github.com/eastkap)

## License

This project is licensed under the MIT License. Still, I would very much like to learn about your results and how you used the data.

## Acknowledgments

* Big thanks to [remmmmmm](https://github.com/remmmmmm) and [Batou](https://github.com/ImBatou) for supporting me (more than you think).
* Hat tip to anyone whose code was used
