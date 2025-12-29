Attacks and Defence Architecture

 <img src="attack.png" width="600">

<img align='right' src="https://media.giphy.com/media/ieyl9zmCjO4b4t6qoY/giphy.gif" width="230"> <p> <em> 


```javascript

[ External Attacker ]  ----------- [ Firewell ] --------- [ Internet ] ------ [ Secure VPN Channel  ]
                                       :
                              [  Management VLAN   ]
                                              ----->   Management Traffic Only
                                    :
                ------------- [   Admin Jumpbox  ] -----------------
                :               ----->    secure admine access     :
                :                                                  :
      [Internet Network ]           <---------->                 [ User Network ]
        Servers/AD/ISE          [Monitoring & Control]            Devices & Users




