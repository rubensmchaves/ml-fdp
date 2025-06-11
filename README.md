# Nonstationary and Imbalanced Dataset for Financial Distress Prediction

Identifying financial distress is critical for companies, investors, and regulatory authorities. The dataset used in this study provides real-world indicators of Brazilian enterprises, based on quarterly data from the Brazilian Securities and Exchange Commission (CVM), and is characterized by nonstationarity. It spans over 10 years and includes 84 financial indicators. The data is highly imbalanced: around 3% of the records correspond to companies in financial distress, while the remaining 97% represent non-distressed firms.

When a enterprise is identified in a financial distress situation we label it as 1. Otherwise the enterprise is considered in normal operation (0), see column LABEL. Due to the enterprise's business area, there is no accounting information in the CVM's data files. In this case, the accounting information value is set to zero. For example, a bank balance sheet has no inventory information, so it is zero. Thus, dataset has no missing values or synthetic and imputed added values.

## Attribute information

| Column       | Description                                                                                       |
|--------------|---------------------------------------------------------------------------------------------------|
| ID           | Sequential value for different enterprises |
| QUARTER      | The last day of the quarter *e.g.* '2011-03-31', '2011-06-30', '2011-09-30' and '2011-12-31' for the first, second, third and fourth quarters, respectively.|
| A1           | Total assets |
| A2           | Current assets |
| A3           | Availability |
| A4           | Receivables |
| A5           | Inventory |
| A6           | Long-term assets |
| A7           | Intangible assets |
| A8           | Tangible assets |
| A9           | Fixed assets |
| A10          | Accumulated depreciation |
| A11          | Accumulated amortization |
| A12          | Investments |
| A13          | Total liabilities |
| A14          | Current liabilities |
| A15          | Non-current liabilities |
| A16          | Commitments (A13 - A14) |
| A17          | Net worth (A12 - A15) |
| A18          | Share capital |
| A19          | Reserves (revenue reserves + capital reserves + non-cash reserve)|
| A20          | Provisions |
| A21          | Long term loan |
| A22          | Gross income |
| A23          | Expenses |
| A24          | Net earnings |
| A25          | Operating expenses |
| A26          | Operating profit |
| A27          | Financial result |
| A28          | Financial expenses |
| A29          | Profit before tax |
| A30          | Tax expenses |
| A31          | Net income |
| A32          | Cash flows from operating activities |
| A33          | Cash Flows from Investing |
| A34          | Cash Flows from Financing |
| A35          | Outstanding shares |
| A36          | Current ratio |
| A37          | Quick ratio |
| A38          | Cash ratio |
| A39          | Interest coverage ratio |
| A40          | Debt ratio |
| A41          | Tangible asset coverage ratio |
| A42          | Ratio of equity to debt |
| A43          | Ratio of commitments to tangible assets |
| A44          | Liquidity ratio |
| A45          | Receivable assets ratio |
| A46          | Fixed Asset Ratio (FAR) |
| A47          | Ratio of stockholders’ equity to fixed assets |
| A48          | Current debt ratio |
| A49          | Operating net profit ratio |
| A50          | Ratio of receivables to gross income |
| A51          | Ratio of inventory to income |
| A52          | Inventory turnover |
| A53          | Turnover ratio of account payable |
| A54          | Turnover of current assets |
| A55          | Ratio of fixed assets to income |
| A56          | Total capital turnover |
| A57          | Return On Assets (ROA) |
| A58          | Ratio of net profit to total assets |
| A59          | Ratio of net profit to current assets |
| A60          | Ratio of net profit fixed assets |
| A61          | Return On Equity (ROE) |
| A62          | Operating profit ratio |
| A63          | Ratio of total operating cost to gross revenue |
| A64          | Expenses to sales Ratio (ER) |
| A65          | Management Expense Ratio (MER) |
| A66          | Financial Expense Ratio (FER) |
| A67          | Free Cash Flow (FCF) |
| A68          | Ratio of operating cash to net profit |
| A69          | Ratio of operating cash to income |
| A70          | Cash recovery rate |
| A71          | Financial leverage |
| A72          | Operational leverage |
| A73          | Combined leverage |
| A74          | Growth of capital maintenance rate |
| A75          | Growth of capital accumulation rate |
| A76          | Growth of total assets rate |
| A77          | Growth rate of ROE |
| A78          | Growth rate of net profit |
| A79          | Growth rate of operating profit |
| A80          | Growth rate of operating receipt |
| A81          | Growth rate of operating cost |
| A82          | Earnings per share |
| A83          | Net asset value per share (NAVPS) |
| A84          | Net cash per share |
| LABEL        | 0: normal situation; 1: financial distress situation |
