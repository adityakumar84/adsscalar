# adsscalar

This project has two parts to it. 

	# Placing ad
		1. Sell
		2. Buy

	# Creating New Category
		1. New Category


# Category Service
	This service is responsible to maintain the schema of all the category. The schema is responsible of maintaing the render of the category HTML (REST SERVICE). ref: https://github.com/rjsf-team/react-jsonschema-form

# Item Service
	This service is responsible for all business logics. 
	1. Sell
	2. Buy

# Database
	1. Cassandra - For saving all events and transactions
	2. Default Sink - Elastic search (for search and relative search)
	3. Caonfigured Sink - Any other sink we want to push data into so that it can be used for data modeling and client segmentation (DATAPLATFORM)