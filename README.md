<img src="https://i.imgur.com/XS79fTC.png" width=200> <img width="100" alt="mozilla-builders" src="https://user-images.githubusercontent.com/1423657/81992335-85346480-9643-11ea-8754-8275e98e06bc.png">


# DPU-MEET: dWebRTC

DPU-MEET is a semi-decentralized conference bridge using modern WebRTC, [GunDB](http://gun.eco) and [MediaSoup](https://mediasoup.org/) to produce a hybrid MESH-SFU with strong privacy, zero user data retention and powerful off-grid capabilities.






<br/>



### Installation
#### Docker

#### Manual
* Install `pm2`
```
sudo npm install pm2 -g
```
* Clone the repository and install using `npm`
```
npm install
```
#### Configuration
* Copy the example `meething.config.example.js` to `meething.config.js`
* Customize `meething.config.js` to set the desired port and other environment variables
* Configure your SSL certificate &amp; key in `certs/` by either copying `certs/fullchain.pem.example` to `certs/fullchain.pem` and `certs/privkey.pem.example` to `certs/privkey.pem` or using your own certificate &amp; key
* Run using pm2
```
pm2 start meething.config.js
```

### Usage
* Browse to the configured HTTPS port _(default 3443)_
* Accept the self-signed certificates _(if needed)_
* Choose a Room and User name
* Share link with other participants

The DPU-MEET application will connect to community Gun nodes for user discovery. All room data/audio/video is p2p.


#### SuperPeers
SuperPeers can provide the network with services such as STUN/TURN/RELAY and in the future SFU/MCU features. For more details, check out the Project Wiki.

<!--

--------------

## Screenshots


#### Isolation Test @qxip @amark @qvdev
<img src="https://user-images.githubusercontent.com/1423657/77968595-04661700-72e8-11ea-8226-b90fbe8011c8.png" width=500 />
<img src="https://user-images.githubusercontent.com/1423657/77922600-8b43d100-72a1-11ea-9879-8e7751fde140.png" width=500 />

#### 0.1 w/ @yeetmydog
<img src="https://user-images.githubusercontent.com/1423657/77825853-43d80c00-710c-11ea-917c-83c2ddd08959.png" width=500/>

-->

-------------





