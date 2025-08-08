# Capital Gains Taxes (Portugal)

This is focused on capital gains from stocks, ETFs and dividends. But more can be added in the future.

## 1. What are Capital Gains?

Capital gains are the profits you make when you sell an asset for more than you paid for it. For example, if you buy a stock for €100 and sell it for €150, you have made a capital gain of €50.

## 2. How are Capital Gains Taxed?

In Portugal, capital gains are generally taxed at a rate of 28%. This means that if you have **a capital gain** of €100, you will have to pay €28 in taxes (28% of €100).

### 2.1 How can I lower this tax?

#### 2.1.1 Long-term capital gain

In Portugal, you pay a lower tax rate if you have a long-term capital gain. This is defined as a gain that you have held for more time. Below you have a table and the tax rate you pay depending on the holding period.

| Holding Period | Tax Rate |
|----------------|----------|
| 0-2 year       | 28.0%      |
| 2-5 years      | 25.2%      |
| 5-8 years      | 22.4%      |
| >8 years       | 19.6%      |

#### 2.1.2 Englobamento

You can also lower your tax rate by doing "englobamento" of the assets. This means that you will group all the assets you have in the same tax rate of your IRS. This is beneficial for the ones that have low to medium income and are taxed at a lower rate than 28%. This is usually for the ones that have a "collectable" income (this is the income that is taxed by the government) lower than €21.321 (in 2024).

## 3. How to Calculate Capital Gains?

Usually people will have the help of accountants to calculate the capital gains since this can be a grueling process. To make our lives easier, we will want to have a spreadsheet that will help us calculate the capital gains. In this spreadsheet, we want to initially keep track of all the transactions that we are doing.

*   **Stock:** This is for you, to identify the asset, for example "Apple" or "Amazon".
*   **Date of Transaction:** The date you bought or sold the asset.
*   **Operation:** This is the operation you are doing, for example "Buy" or "Sell".
*   **Price:** The price you paid or sold each asset.
*   **Quantity:** The quantity of the asset you are buying or selling.
*   **Trade Expenses:** The commission charged by the broker.

And an example of this would be:

| Stock | Date of Transaction | Operation | Price | Quantity | Trade Expenses |
|-------|---------------------|-----------|-------|----------|----------------|
| Apple | 2024-01-01          | Buy       | 150   | 1        | 2              |
| Apple | 2024-01-02          | Buy       | 155   | 1        | 1              |
| Apple | 2024-01-03          | Sell      | 160   | 1        | 1              |

This table is your raw data, but for declaring your capital gains, we will need to calculate the difference between the price you paid and the price you sold. To correctly assign the asset you are selling to the asset you bought, **we will have to follow the FIFO (First In, First Out) method**. This means that the first asset you bought is the first asset you will sell, otherwise you could always keep the oldest.

To have this final "Capital Gains" table, we will join some of the rows from the previous table. We will want to have the following columns:

*   **Date of Purchase:** The date you bought the asset**s** (Remember to follow the FIFO rule)
*   **Date of Sale:** The date you sold the assets.
*   **Price of Purchase:** The price you paid for all the assets.
*   **Price of Sale:** The price you sold all the assets for.
*   **Market Location (País da Fonte):**  This is the country of the Stock Exchange where the share is listed. Even if it is Apple, you might be buying it in the Amsterdam Stock Exchange, so the country would be "Netherlands".
*   **Trade Expenses:** The total commissions you had to pay to buy **and** sell the asset. For this I sometimes have to do a weighted average.

And an example of this would be:

| Date of Purchase | Date of Sale | Price of Purchase | Price of Sale | Market Location (País da Fonte) | Trade Expenses |
|------------------|--------------|------------------|---------------|--------------------------------|----------------|
| 2024-01-01       | 2024-01-03   | 150              | 160           | Netherlands                    | 3              |


## 4. How to keep track of dividends?

Dividends are a lot simpler. Just be sure to keep track of:

*   **Date of Dividend:** The date you received the dividend.
*   **Country:** The country of where the asset belongs to.
*   **Dividend Value:** The amount of money you received from the dividend.
*   **Tax Paid:** The amount of tax you paid on the dividend. This is the tax paid in the country of the company you have assets in. For example, if you have a US company, you will have to pay 15% tax, and Portugal will tax you the remaining 13% for the 28% Portuguese tax.

If your broker is already retaining some tax for the Portuguese government, you also need to keep track of the NIF of the broker and the amount that was retained. I know in Degiro it doesn't do that.

## 5. What do I need to declare in the IRS?

This will depend if the broker is foreign or national:

If you are declaring stocks and ETFs from a **foreign broker** (like Degiro, XTB, etc.), you will need to fill in the Annex J, table 9.2. For stocks you use the code G01 and for ETFs you use the code G20. As for the "País da Fonte", this is the country of the Stock Exchange where the share is listed. Even if it is Apple, you might be buying it in the Amsterdam Stock Exchange. And "País da Contraparte" is the country of the broker. At least this is the convention, but not even AT seems to be sure about this...

If you are declaring stocks and ETFs from a **national broker** (like Banco Português de Investimento, etc.), you will need to fill in the Annex G, table 9. The codes are the same as the ones for the foreign trader (G01 and G20). To do "englobamento" of the assets, you will need to fill in the Annex G, table 15.

As for dividends, like stocks and ETFs, you have to fill in different tables depending on where the broker is located.

If you are declaring dividends from a **foreign broker** (like Degiro, XTB, etc.), you will need to fill in the Annex J, table 8A with code E11. Here we should fill in one line **per country**. Also, don't forget to fill in the Tax paid in the country of the company you have assets in. This is the "No país da fonte" column and it should be the absolute value of the tax paid. For example, for US companies, you should have already paid 15% tax, and Portugal will tax you the remaining 13% for the 28% Portuguese tax. In this case, "País da fonte" should be "US" since the asset is for a US company.

If you are declaring dividends from a **national broker** (like Banco Português de Investimento, etc.), you don't need to declare because they are already retained by the broker. But! If you want to do "englobamento" of the assets, you will need to fill in the Annex E , table 4B with the code E10.

## 6. What about Crypto?

Crypto is a bit different. You will always have to declare them anytime you sell, you do this in the Annex G1, table 7. But the golden rule for crypto in Portugal is that if you keep cryptoactive assets for more than 365 days, you will not be taxed on the gains.
