## Purchase Rate Tracker

A browser-based purchase rate intelligence tool that ingests structured, pre defined and clean raw material purchase register data and 
automatically flags price anomalies, compares vendor rates, and generates audit-ready PDF reports 
— no backend, no installation, runs entirely client-side.

**Key Features**
- Automated rate-spike/drop detection with configurable alert thresholds (previously no such check existed)
- Vendor comparison engine — identifies lowest-rate vendor per item across purchase history
- Interactive dashboards: monthly purchase trends, top 10 items/vendors by spend, spike distribution
- One-click PDF exports: date-wise, item-wise, and vendor-wise reports (with tables, headers, formatting)
- Client-side Excel ingestion with column auto-mapping, filtering, search, and pagination

**Tech Stack**
Vanilla JavaScript, HTML5/CSS3, SheetJS (XLSX parsing), Chart.js (data viz), jsPDF + AutoTable (report generation)

**Impact**
- Processes 5,000+ purchase records across 100+ vendors per run
- Flagged ₹15,000–20,000 in rate overpayments across 10-12 vendors via automated alerts
- Replaced a manual, ad-hoc rate-checking process with zero prior anomaly detection

