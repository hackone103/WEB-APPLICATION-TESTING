 # Shodan Dorks
*Dorks for shodan.io* website. Taken from publicly available sources.

_This is the list of most interesting shodan dorks that you can use on Shodan.io_
omputers (webcams, routers, servers, etc.) connected to the internet using a variety of filters._

## Basic Shodan Filters
### hostname:
Find devices matching the hostname.:<br/>
`server: "gws" `\
`hostname:"google"`\
`hostname:example.com`\
`hostname:subdomain.example.com`\
`hostname:example.com,example.org`

### net:
Find devices based on an IP address or /x CIDR.<br/>
`net:210.214.0.0/16`

### Organization
`org:microsoft`
`org:"United States Department"`


### YOU CAN ALSO COMBINE FILTERS TO MAKE INTO ADVANCED FILTERS FOR QUICK RECON.

*Please create a pull request if you want to contribute.*
