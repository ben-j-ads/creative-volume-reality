# Creative Volume Reality

How many genuinely different ad concepts can your budget actually tell apart? Enter the budget for one test round, your cost per result and how many concepts you want to test, and see how many one round can read, and the rounds and money it takes to get through all of them.

Open `index.html` in any browser. No build step, no dependencies, no network calls.

- **Headline:** how many concepts one round can read at a 25% gap, or `not even two`.
- **Three levels:** big swings only (50% gap), a solid read (25%) and a fine read (10%), each with the concepts one round can read and the results each gets.
- **Plan:** for the number of concepts you want to test, the rounds and total budget at each level. Each round carries the best concept so far against fresh challengers.
- **Calculation:** C = 2 x ((z + zb) / ln(1 + gap))^2 results per concept, with a Sidak correction for the k - 1 comparisons against the best concept. Confidence and power are adjustable.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

A rebuild of creative-test-budget with fewer inputs and a plan view. Assumes an even budget split and counts of rare events, and platforms rarely deliver evenly inside one ad set, so use separate ad sets or a split test. The cheapest result is not always the best sale. Pairs with abverdict, which reads the test once it has run.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
