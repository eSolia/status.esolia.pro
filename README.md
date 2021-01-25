![deploy-production](https://github.com/RickCogley/esolia-status/workflows/deploy-production/badge.svg?branch=master)

The excellent [Ping](https://ping.apex.sh) service from [@Apex](https://github.com/apex/), can serve status pages on their domain as secure httpS, and while you can specify a cname, you end up needing to use httP, since the Apex SSL cert does not cover your domain. 

The solution is to embed each status page in an `<iframe>` tag on your own secured pages, and that is what this simple site does. (I hate iframes, but it works in this case)

This site is built by hand, and published to AWS via [Apex.sh](https://apex.sh) «[up](https://apex.sh/up/)». 


