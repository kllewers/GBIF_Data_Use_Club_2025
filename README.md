1. Google Earth Engine (GEE)
Sign up for a GEE account and wait for approval (may take up to 1–2 days).
Signup link: https://earthengine.google.com/signup/
Documentation: https://developers.google.com/earth-engine/guides/python_install, you should only have to authenticate once
2. NASA Earthdata / Earthaccess
Create a NASA Earthdata Login (used for accessing data via the earthaccess Python library).
Signup link: https://urs.earthdata.nasa.gov/users/new
3. GBIF API via pyGBIF
No formal account is needed to use pygbif, but you will need a GBIF account to download occurrence data.
Signup link: https://www.gbif.org/user/profile
pyGBIF Docs & Installation: https://pypi.org/project/pygbif/
Recommended Python Environment
We'll be using Python (≥3.10) and recommend setting up a virtual environment (ie: python venv or conda) with the following packages:
pip install earthengine-api earthaccess pygbif
