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



``` </"img src="attack/attack.png" width="600>
