npm install
npm start

run docker server
docker run -p 4443:4443 --rm -e openvidu.secret=MY_SECRET -e openvidu.publicurl=https://YOUR_IP:4443/ openvidu/openvidu-server-kms:2.12.0
