# Beast Games Prize & Tax Calculator

An open-source estimator that answers the question every Beast Games fan asks: **if you win the $5 million, how much do you actually keep?**

Game show winnings in the United States are taxed as ordinary income. The headline prize and the spendable prize are two very different numbers. This calculator shows the gap.

**Try the live version:** the [Beast Games prize and tax calculator](https://realitytrending.com/) runs on Reality Trending, with the full season coverage around it.

For the long explanation of brackets, withholding and state differences, read the companion guide: [Beast Games prize money taxes](https://realitytrending.com/beast-games-season-2-taxes/).

## What it does

- Enter any prize amount (the Beast Games prize defaults to $5,000,000)
- Optionally subtract in-show deductions, such as bribes a contestant accepted during the games
- Pick the winner's home state (state tax is where the answers really split)
- See the estimated federal tax, state tax, and the take-home amount

## How the estimate works

- **Federal:** simplified model at the 37% top federal rate, the bracket a multi-million prize lands in. This matches the live calculator on Reality Trending.
- **State:** the top state rate for the selected state. States with no income tax (Nevada, Texas, Florida and others) are listed at 0%.
- **Withholding note:** shows and studios usually withhold 24% before paying out, which is typically less than the final bill. The remainder comes due when the winner files.

## Run it locally

It is a single self-contained page. Open `index.html` in any browser. No build step, no dependencies.

## Disclaimer

This is a fan-made educational estimate, not tax advice. Real outcomes depend on filing status, deductions, residency rules and the tax year. Anyone who actually wins should hire a good accountant before spending anything.

## License

MIT. Use it, fork it, improve it.

Maintained by [Reality Trending](https://realitytrending.com/), an independent Beast Games and reality TV news site covering casting, filming, contestants and prize money.
