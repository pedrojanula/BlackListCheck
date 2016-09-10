# BlackListCheck

BlackListCheck is a app that tells you if an IP address or domain name has been reported by illegal activities.

**Demo**: [BlackListCheck](http://blacklistcheck.pedrojanula.xyz/)

## Requeriments
1. A Web Server (Apache, Nginx...) [OPTIONAL]

*(No need a web server. It's optional)*
 

## Installation
1. Clone this repository
```bash
git clone https://github.com/pedrojanula/BlackListCheck
```
2. Open `index.html` to use.


## Includes
You don't need to include anything more. 

This app uses an external API for get data: [Cymon API](https://cymon.io/cp/api)

## Limits

The Cymon API is limited to 500 request per day (without API Key)


## Usage

1. Run `index.html`
2. Enter an IP address or domain name.
3. Press `CHECK` button to start.
4. If the IP address or domain name is on a blacklist, the information is displayed.


##### Aditional Info: 
**www.domain.com and domain.com are two different directions. You may www.domain.com is reported but domain.com is not.**