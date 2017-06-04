# mifid2

https://fasterxml.github.io/jackson-databind/javadoc/2.7/com/fasterxml/jackson/databind/SerializationFeature.html#ORDER_MAP_ENTRIES_BY_KEYS

<pre>
ISIN is the key for RTS23 (standard for instrument reference data report), meaning ISIN can't be less granular than RTS23 (but can be more granular)
ISIN is mandantory field for RTS 22, T+1 transaction reporting (field 41)
ISIN is also required for post-trade transparency under RTS2 (which also inlcludes pre-trade transparency)
in one word - ISIN is not needed for pre-trade

ANNA-DSB ISIN final report: http://www.anna-web.org/wp-content/uploads/2016/12/DSBTO-CP001-Final-Report-v1.1.pdf
ANNA-DSB ISIN latency: 99% below 1,000ms
ANNA-DSB ISIN bursts: 60,000/minute from 200 users
ANNA-DSB ISIN connectivity: VPN or SSL
ANNA-DSB ISIN availability: 24x6, 99.99%
ANNA-DSB ISIN storage: 7 years log, record forever
ANNA-DSB ISIN DR: 4 hours, annual test
ANNA-DSB ISIN production live: 02/10/2017
</pre>

<pre>
question: https://www.esma.europa.eu/sites/default/files/library/esma00-6-265_note_on_mifid_reporting_0.pdf 
july 2017?
</pre>
