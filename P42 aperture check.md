#CERN #ECN3 

### Similar names
#### Different locations
|s_st|d_s|d_l|keyword_st|keyword_reb|apertype_st|apertype_reb|d_aper_1|d_aper_2|
|---|---|---|---|---|---|---|---|---|
|bbs.x0450837|1716.120641|0.140171|0.0|instrument|marker|circle|circle|0.0|0.0|
|bsi.x0450837|1716.120641|0.140171|0.0|instrument|marker|circle|circle|0.0|0.0|
|tbiu.x0450837|1716.120641|0.140171|0.0|instrument|marker|circle|circle|0.0|0.0|

#### Different apertures
Had different apertures:

|index|type|aper_1_st|aper_2_st|d_aper_1|d_aper_2|num|
|---|---|---|---|---|---|---|
|0|mbb|0.0000|0.0000|-0.0597|-0.02425|4|
|1|mbnh|0.0745|0.0260|0.0095|-0.00400|13|
|2|mbnv|0.0745|0.0260|0.0095|-0.00400|2|
|3|mbw|0.0630|0.0225|-0.0015|-0.00350|5|
|4|mdsh|0.0000|0.0000|-0.0605|-0.03150|2|
|5|msn|0.0470|0.0260|-0.0100|-0.00400|2|
|6|mtn|0.1865|0.0285|0.0665|-0.00150|2|
|7|qnl|0.0385|0.0000|-0.0015|-0.04000|23|
|8|qsl|0.0460|0.0000|-0.0040|-0.05000|1|

Had no apertures:

|index|type|aper_1_st|aper_2_st|d_aper_1|d_aper_2|num|
|---|---|---|---|---|---|---|
|0|bbsth|0.0725|0.0725|0.0725|0.0725|1|
|1|bbstv|0.0725|0.0725|0.0725|0.0725|1|
|2|bsi|0.0725|0.0725|0.0725|0.0725|1|
|3|bsph|0.0725|0.0725|0.0725|0.0725|1|
|4|mbxgd|0.0630|0.0295|0.0630|0.0295|1|
|5|mcxca|0.0360|0.0000|0.0360|0.0000|9|
|6|mdsh|0.0630|0.0295|0.0630|0.0295|1|
|7|tbid|0.0725|0.0725|0.0725|0.0725|3|
|8|xchv|0.0500|0.0500|0.0500|0.0500|4|
|9|xtcx|0.0450|0.0000|0.0450|0.0000|1|
|10|xtcx|0.0600|0.0000|0.0600|0.0000|1|
|11|xvw|0.1750|0.0300|0.1750|0.0300|2|
|12|xvw|0.4300|0.0300|0.4300|0.0300|1|
According to [Luke's comment](https://its.cern.ch/jira/secure/RapidBoard.jspa?rapidView=8101&projectKey=SEXTWG&view=detail&selectedIssue=SEXTWG-16#:~:text=added%20a%20comment%20%2D-,24/Nov/23%2010%3A40%20AM,-I%20am%20adding) we need to understand why QSL, MBNH/V, MBW, MBXGD/MCW, MTN, MSN apertures are different in the stitched model.

MDS:
https://norma-db.web.cern.ch/magnet/idcard/5020/ (130 x 69 mm^2 aperture)
horizontal ones in tt21 have no apertures

MDX/MCXCA:
https://norma-db.web.cern.ch/magnet/idcard/5745/ (80 x 80 mm^2 aperture)

QNL:
https://norma-db.web.cern.ch/magnet/idcard/5235/ (80 x 80 mm^2 aperture)
There are some in tt21 and 24

QSL:
https://norma-db.web.cern.ch/magnet/idcard/5367/ (100 x 100 mm^2 aperture)
there is one in tt22

MBNH/V:
https://norma-db.web.cern.ch/magnet/idcard/6833/ (250 x 60 mm^2 aperture)

MBW:
https://norma-db.web.cern.ch/magnet/idcard/4735/ (129 x 52 mm^2 aperture)

MBXGD/MCW:
https://norma-db.web.cern.ch/magnet/idcard/5642/ (195 x 70 mm^2 aperture)

MTN:
https://norma-db.web.cern.ch/magnet/idcard/6914/ (350 x 60 mm^2 aperture)
In tt24 seq the vertical aperture is incorrect

MSN:
https://norma-db.web.cern.ch/magnet/idcard/5101/ (114 x 60 mm^2 aperture)


