import requests
import json

# Amazon MWS credentials
SELLER_ID = 'your_seller_id'
AWS_ACCESS_KEY_ID = 'your_access_key_id'
SECRET_KEY = 'your_secret_key'
MARKETPLACE_ID = 'your_marketplace_id'

# Product ASIN (Amazon Standard Identification Number)
PRODUCT_ASIN = 'B00X4WHP5E'

# API endpoint for GetLowestOfferListingsForASIN operation
ENDPOINT = 'https://mws.amazonservices.com/Products/2011-10-01'
ACTION = 'GetLowestOfferListingsForASIN'
