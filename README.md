# RentaBiz

Matt & Benji's shared board for exploring residential rental deals in Harrisburg, PA.

Live: https://mattgpt5786.github.io/RentaBiz/

Single-file site (`index.html`). Deals live in the `DEALS` array in the page script;
metrics (cash flow, cap rate, mortgage P&I, rent-to-price) are computed in-browser
from the model assumptions at the top of the script (20% down, 7.0%, 30-yr,
5% vacancy, 5% maintenance). Statuses: Watching / Analyzing / Toured / Passed / Offer.
