# Technical Challenge Overview

For this technical challenge, you are required to use data from an API to recreate the following screen:

![The banking app screen](/public/example.png)

### Requirements

- You are tasked with building a spending breakdown screen for a banking app.
- The screen should display a list of categories along with the total spending for each category.
- _Stretch Goal_ - Allow customers to click/tap on a category to reveal the transactions associated with it below.

The API to fetch Expenses from is located here:
`https://csb-u0slz.vercel.app/api/transactions`

The return type is:

```
type Expense = {
  id: number
  amount: number
  date: string
  name: string
  category: string
}
```
