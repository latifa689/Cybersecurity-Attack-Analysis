Attacks and Defence Architecture

 <img align='right' src="attack.png" width="500">



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




