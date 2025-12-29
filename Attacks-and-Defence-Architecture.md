Attacks and Defence Architecture

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


</"img src="images/"attack.png"width="700>
