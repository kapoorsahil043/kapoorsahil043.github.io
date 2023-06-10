# https://reactrouter.com/en/main/start/tutorial

# cordova platform install
cordova platform add browser

# cordova plugins install
cordova plugin add cordova-plugin-geolocation


# npm package
npm i rimraf
npm i redux react-redux redux-devtools-exdux react-redux redux-devtools-extension
npm i axios
npm install classnames // for custom alert msg
# https://blog.logrocket.com/push-notifications-react-firebase/#firebase-setup
npm install --save firebase
npm install formik --save
npm install yup --save
npm install react-razorpay
npm install react-bootstrap // customtooltip.js
npm install jwt-decode / jwt
npm install fingerprintjs2 // Prints the device ID
npm install node-forge // encrpyt password


# start cordova app
cordova run browser


# sample data
5214 4789 0000 5330
03 25 123

# authorization
http://localhost:3000/subscription?payment_id=MOJO3503605A78633838&payment_status=Failed&payment_request_id=065f2fffbbe04499a81677b2d3a60bab

# authetication
http://localhost:3000/subscription?payment_id=MOJO3503F05A78633837&payment_status=Failed&payment_request_id=086e3d93c0bd428294b99aa2c4d8223d

# success
http://localhost:3000/subscription?payment_id=MOJO3502J05A81417103&payment_status=Credit&payment_request_id=64572f4d8edc5e47fe0774bc

# failed / money debited
http://localhost:3000/subscription?payment_id=MOJO3503M05A78633835&payment_status=Failed&payment_request_id=c122a538bc194e0daafc4a47f0bdd4e5

# failed/ cancel
http://localhost:3000/subscription?payment_id=MOJO3503D05A78633834&payment_status=Failed&payment_request_id=645734a1ef4a6d72aaa76f74