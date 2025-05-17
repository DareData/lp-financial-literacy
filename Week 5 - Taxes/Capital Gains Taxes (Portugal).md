# Capital Gains Taxes (Portugal)

This is focused on capital gains from stocks, ETFs and dividends. But more can be added in the future.

## 1. What are Capital Gains?

Capital gains are the profits you make when you sell an asset for more than you paid for it. For example, if you buy a stock for €100 and sell it for €150, you have made a capital gain of €50.

## 2. How are Capital Gains Taxed?

In Portugal, capital gains are generally taxed at a rate of 28%. This means that if you have **a capital gain** of €100, you will have to pay €28 in taxes (28% of €100).

## 3. How to Calculate Capital Gains?

Usually people will have the help of accountants to calculate the capital gains since this can be a grueling process. To make our lives easier, we will want to have a spreadsheet that will help us calculate the capital gains. In this spreadsheet, we want to initially keep track of all the transactions that we are doing.

*   **Stock:** This is for you, to identify the asset, for example "Apple" or "Amazon".
*   **Date of Purchase:** The date you bought the asset.
*   **Operation:** This is the operation you are doing, for example "Buy" or "Sell".
*   **Price:** The price you paid for each asset.
*   **Quantity:** The quantity of the asset you are buying or selling.
*   **Trade Expenses:** The expenses you had to pay to buy or sell the asset.


This would be your raw data, but for declaring your capital gains, we will need to process this information so we can calculate the capital gains. To correctly assign the asset you are selling to the asset you bought, we will have to follow the FIFO (First In, First Out) method. This means that the first asset you bought is the first asset you will sell.

To do this, we will want to have a column that will help us calculate the capital gains. In this final table, we will want to have the following columns:

*   **Date of Purchase:** The date you bought the asset**s** 
*   **Date of Sale:** The date you sold the assets.
*   **Price of Purchase:** The price you paid for all the assets.
*   **Price of Sale:** The price you sold all the assets for.
*   **Market Location (País da Fonte):**  This is the country of the Stock Exchange where the share is listed. Even if it is Apple, you might be buying it in the Amsterdam Stock Exchange.
*   **Trade Expenses:** The expenses you had to pay to buy **and** sell the asset. For this I sometimes have to do a weighted average.

## 4. How to keep track of dividends?

Dividends are a lot simpler. Just be sure to keep track of:

*   **Date of Dividend:** The date you received the dividend.
*   **Country:** The country of where the asset belongs to.
*   **Dividend Amount:** The amount of the dividend you received.
*   **Tax Paid:** The amount of tax you paid on the dividend.

If your broker is already retaining some tax for the Portuguese government, you also need to keep track of the NIF of the broker and the amount that was retained.

## 5. What do I need to declare in the IRS?

This will depend on two things:

If you are declaring stocks and ETFs from a **foreign broker** (like Degiro, XTB, etc.), you will need to fill in the Annex J, table 9.2. For stocks you use the code G01 and for ETFs you use the code G20. As for the "País da Fonte", this is the country of the Stock Exchange where the share is listed. Even if it is Apple, you might be buying it in the Amsterdam Stock Exchange. And "País da Contraparte" is the country of the broker. At least this is the convention, but not even AT seems to be sure about this...

If you are declaring stocks and ETFs from a **national broker** (like Banco Português de Investimento, etc.), you will need to fill in the Annex G, table 9. The codes are the same as the ones for the foreign trader (G01 and G20). To do "englobamento" of the assets, you will need to fill in the Annex G, table 15.

As for dividends, like stocks and ETFs, you have to fill in different tables depending on where the broker is located.

If you are declaring dividends from a **foreign broker** (like Degiro, XTB, etc.), you will need to fill in the Annex J, table 8A with code E11. Here we should fill in one line **per country**. Also, don't forget to fill in the Tax paid in the country of the company you have assets in. This is the "No país da fonte" column and it should be the absolute value of the tax paid. For example, for US companies, you should have already paid 15% tax, and Portugal will tax you the remaining 13% for the 28% Portuguese tax. In this case, "País da fonte" should be "US" since the asset is for a US company.

If you are declaring dividends from a **national broker** (like Banco Português de Investimento, etc.), you don't need to declare because they are already retained by the broker. But! If you want to do "englobamento" of the assets, you will need to fill in the Annex E , table 4B with the code E10.

## 6. What about Crypto?

Crypto is a bit different. You will always have to declare them anytime you sell, you do this in the Annex G1, table 7. But the golden rule for crypto in Portugal is that if you keep cryptoactive assets for more than 365 days, you will not be taxed on the gains.


