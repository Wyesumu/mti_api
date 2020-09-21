# mti_api
Simple realization of API for api.mti.ua on python

Example:

import mti_api

mti = mti_api.MTI(config.key, config.company) #create class instance

result = mti.make_request('price', {'store_id':'W600'}) #call make_request and send command and dictionary of params
print(result)
