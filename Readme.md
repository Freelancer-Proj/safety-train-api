
Secret key to decode jwt 

SECRET_KEY = 'abc'

token decode : jwt.encode({'id' : data_return['id'], 'role' : data_return['role_id'], 'exp' : time_exp )

- Document ref: 
  - user api: https://raw.githubusercontent.com/Freelancer-Proj/safety-train-api/master/api_yaml/api_user.yaml
  - role user city: https://raw.githubusercontent.com/Freelancer-Proj/safety-train-api/master/api_yaml/api_role_user_city.yaml
  - role cam user: https://raw.githubusercontent.com/Freelancer-Proj/safety-train-api/master/api_yaml/api_role_cam_user.yaml
  - machine: https://raw.githubusercontent.com/Freelancer-Proj/safety-train-api/master/api_yaml/api_machine.yaml
  - city: https://raw.githubusercontent.com/Freelancer-Proj/safety-train-api/master/api_yaml/api_city.yaml
  - camera: https://raw.githubusercontent.com/Freelancer-Proj/safety-train-api/master/api_yaml/api_camera.yaml

- Pass url into https://editor.swagger.io/ to see the format API.
