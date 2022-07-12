# Notice

## Project is live for public usage. [Custom filter](https://dnswarden.com/customfilter.html) dns is live, you try it out [here](https://dnswarden.com/customfilter.html).




#### Just a normal privacy oriented dns service with a ability to block ads , trackers and also provides uncensored dns! 



## Features

* Provides multiple types of dns 
  * **Pure uncensored dns** (Blocks nothings , more power for the user!)
  * **Adblocking dns** (Blocks ads , trackers and all the random crap on the internet.)
  * **Adult Filter dns** ( Blocks adult content, enforces force safe search for search engines and youtube. Also blocks ads,trackers and other malicious stuff)
  * **Custom filter dns** ( Users can choose multiple blocklists from the predefined set depending on their usage. Only supports DNS-over-TLS and DNS-over-HTTPS)
  

    * Supports DNSCrypt , DNS over HTTPS and DNS over TLS .
    * DNSSEC and [QNAME minimization](https://tools.ietf.org/html/rfc7816) are enabled by default.
    * Supports other [non-icann TLD's](https://github.com/bhanupratapys/dnswarden/issues/7#issuecomment-548266343).
    * No query logging .
    * If your favourite website gets blocked/broken , report **[ here](https://github.com/dnswarden/blocklist-staging)** or **[ here](https://t.me/dnswarden)** or **[ here](mailto:dns-support@dnswarden.com)**. No support will be given to custom filter dns for broken/blocked sites. Users will have to choose the blocklist appropriately. 
    
    
 # Server information
 
* ## Adblocking DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  adblock.dns.dnswarden.com
  
  * ### DNS-over-HTTPS: 
    *  https://dns.dnswarden.com/adblock
    *  [Stamps](https://github.com/bhanupratapys/dnswarden/tree/master/stamps/DoH/adblock).

    
  * ### DnsCrypt
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adblock/France.md) for server at France.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adblock/India.md) for server at India.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adblock/Singapore.md) for server at Singapore.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adblock/USA.md) for server at USA.
         
         
   


   

       
* ## Uncensored DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  uncensored.dns.dnswarden.com
  
  * ### DNS-over-HTTPS: 
    *  https://dns.dnswarden.com/uncensored
    *  [Stamps](https://github.com/bhanupratapys/dnswarden/tree/master/stamps/DoH/uncensored).
 
    
    
  * ### DnsCrypt

      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/uncensored/France.md) for server at France.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/uncensored/India.md) for server at India.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/uncensored/Singapore.md) for server at Singapore.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/uncensored/USA.md) for server at USA.

          

       
       
* ## Adult Filter DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  adultfilter.dns.dnswarden.com
  
  * ### DNS-over-HTTPS: 
    *  https://dns.dnswarden.com/adultfilter
    *  [Stamps](https://github.com/bhanupratapys/dnswarden/tree/master/stamps/DoH/adultfilter).

    
    
  * ### DnsCrypt
  
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adultfilter/France.md) for server at France.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adultfilter/India.md) for server at India.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adultfilter/Singapore.md) for server at Singapore.
      
      * [Stamps](https://github.com/bhanupratapys/dnswarden/blob/master/stamps/DnsCrypt/adultfilter/USA.md) for server at USA.



       
* ## Privacy policy and T&C
  * Use at your own risk. I will not be held responsible for any downtime of the servers , only on a "best effort" basis.
  * No query logging . Completely disabled query logs related to the DNS traffic.
  * Dns traffic will be forwarded datacenter's dns servers if the resolver fails. 





* ### Client software

    * Android
      * [Dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy), Supports dnscrypt and DoH. Also supports other os's.
      * [InviZible Pro](https://f-droid.org/en/packages/pan.alexander.tordnscrypt.stable), Supports dnscrypt and DoH.
      * [Nebulo](https://git.frostnerd.com/PublicAndroidApps/smokescreen#installation), Supports both DoT and DoH.
      * [PersonalDnsFilter](https://zenz-solutions.de/personaldnsfilter), Supports DoT , DoH and normal DNS.
      * [Intra](https://play.google.com/store/apps/details?id=app.intra), Supports only DoH.
      * By using Android Pie , Go to Setting -> Wi-Fi -> Private DNS and enter the hostname. Supports only DoT.
      
     
    * For other OS's
       * [Knot-resolver](https://www.knot-resolver.cz).
       * [Unbound](https://nlnetlabs.nl/projects/unbound/about).
       * [Stubby](https://dnsprivacy.org/wiki/display/DP/DNS+Privacy+Daemon+-+Stubby).
       * [m13253's DoH](https://github.com/m13253/dns-over-https).




