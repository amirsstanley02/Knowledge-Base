# Example 3: Lincoln Electric Holdings (practice sheet)

Source: Lincoln Electric's FY2025 Form 10-K (filed 2026-02-25), pulled from the SEC EDGAR XBRL data. Figures in $ thousands. I grouped some small balance sheet lines (noted below), but every number is the company's reported figure. The balance sheet foots and balances.

Prepare Lincoln Electric's 2025 statement of cash flows using the indirect method. Net income comes from the income statement; use retained earnings to find dividends.

1. Dividends declared = beginning RE + net income - ending RE. Then convert to dividends **paid** using the change in dividends payable.
2. Compare depreciation to the change in accumulated depreciation. This one will NOT tie like Birch did. Work out why (hints in the key).
3. Treat the current portion of debt and long-term debt together as debt. A shift between the two lines is a reclassification, not cash.
4. Prove that ending cash ties to the balance sheet.

**Assumptions and handling of new items (not in Birch):**
- Treat the change in goodwill + intangibles + intangible amortization as **acquisitions** (investing).
- Treat changes in deferred tax, other current/non-current assets and liabilities as operating.
- Treasury stock increases are share buybacks. Additional paid-in capital changes are stock comp / option exercises (financing).
- Accumulated other comprehensive loss (AOCI) moved because of currency translation. It is non-cash. Show it as a final reconciling line.
- Gross PP&E change = capital expenditures (ignore disposals).

## Income statement, year ended December 31, 2025
| ($ thousands) | 2025 |
|---|---|
| Revenue | 4,233,003 |
| Cost of goods sold | (2,698,751) |
| **Gross profit** | **1,534,252** |
| SG&A | (797,994) |
| Rationalization and asset impairment charges | (18,199) |
| **Operating income (EBIT)** | **718,059** |
| Interest expense | (58,379) |
| Interest income | 6,818 |
| Other income, net | 8,952 |
| **Pre-tax income** | **675,450** |
| Income taxes | (154,917) |
| **Net income** | **520,533** |

Memo (from the cash flow statement notes): total depreciation & amortization = 98,546, of which amortization of intangibles = 29,717. (Real companies bury D&A inside COGS and SG&A, so it doesn't appear as its own income statement line like it did for Birch.)

## Balance sheets at December 31
| ($ thousands) | 2024 | 2025 |
|---|---|---|
| **Assets** | | |
| Cash | 377,262 | 308,789 |
| Accounts receivable | 481,979 | 538,791 |
| Inventory | 544,037 | 633,364 |
| Other current assets | 242,003 | 258,568 |
| **Total current assets** | 1,645,281 | 1,739,512 |
| Gross PP&E | 1,484,815 | 1,645,568 |
| Less: accumulated depreciation | (865,634) | (942,806) |
| Net PP&E | 619,181 | 702,762 |
| Goodwill | 804,927 | 886,686 |
| Intangible assets, net | 221,005 | 250,424 |
| Deferred tax assets | 77,611 | 47,077 |
| Other non-current assets | 152,137 | 151,116 |
| **Total assets** | 3,520,142 | 3,777,577 |
| **Liabilities and equity** | | |
| Accounts payable | 296,590 | 364,934 |
| Accrued employee liabilities | 104,374 | 116,158 |
| Other current liabilities | 325,156 | 288,491 |
| Dividends payable | 42,158 | 43,328 |
| Current portion of debt (short-term + current LTD) | 110,524 | 143,780 |
| **Total current liabilities** | 878,802 | 956,691 |
| Long-term debt | 1,150,551 | 1,150,228 |
| Deferred tax liabilities | 10,464 | 52,104 |
| Other non-current liabilities | 152,892 | 148,760 |
| **Total liabilities** | 2,192,709 | 2,307,783 |
| Common stock | 9,858 | 9,858 |
| Additional paid-in capital | 566,740 | 601,566 |
| Retained earnings | 3,993,016 | 4,342,080 |
| Treasury stock (at cost) | (2,942,046) | (3,277,779) |
| Accumulated other comprehensive loss | (300,135) | (205,931) |
| **Total equity** | 1,327,433 | 1,469,794 |
| **Total liabilities and equity** | 3,520,142 | 3,777,577 |

Grouping notes: "Other current liabilities" and "Other non-current assets" include items such as leases and supplier finance obligations. "Current portion of debt" = short-term borrowings + current portion of long-term debt.
