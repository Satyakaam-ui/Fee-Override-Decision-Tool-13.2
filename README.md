# Fee-Override-Decision-Tool-13.2
A Tampermonkey userscript that assists associates in making fast and accurate fee override decisions on Amazon seller tickets by comparing current and proposed fee categories.


Fee Override Decision Tool — v14.0
A Tampermonkey userscript that helps agents make fast, accurate fee override decisions on Amazon seller tickets.
How It Works
Upload your current fee category file once, and the tool instantly cross-references any ticket's ASIN and marketplace against it — giving you a clear Safe ✅ or Caution ⚠️ decision in seconds.
What's New in v14.0
Reverted to a simpler, more reliable direct file upload model instead of the previous DataCentral batch query approach. The tool now works entirely from a locally uploaded fee category file, with no external dependencies.
Steps to Use

Upload Fee Category File — Upload your current fee category XLSX or CSV (asin, marketplace_id, fee_category_name columns needed). Persists across sessions.
Upload Fees Master File — Upload the fees master CSV with fee percentages per category and marketplace. Persists across sessions.
ASIN Processor — Open BadCat or CRISP directly for any ticket's ASINs without switching tabs manually.
Check Decision — Hit the button on any ticket page for an instant override recommendation.

Supported File Formats:

Current Fee Category file --> .xlsx, .xls, .csv
Fee rate Master file --> .csv
