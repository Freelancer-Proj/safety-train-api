
Secret key to decode jwt 

SECRET_KEY = 'abc'

token decode : jwt.encode({'id' : data_return['id'], 'role' : data_return['role_id'], 'exp' : time_exp )