## R-screen

Given a sample data set (fake-claims style data including bene_id, claim_id, date of admit, date of discharge, stay type):

* Flag claims for the same beneficiary that start within 1 day, 30 days, and 180 days of a preceding discharge.

* Summarizes the pattern of stays for each beneficiary including non-stay gaps
