Attacks and Defence Architecture

 <img align='right' src="attack.png" width="500">


## 🛡️ Attack and Defense Architecture

The attack and defense architecture illustrates a **layered security model** designed to minimize exposure and control access points.

By isolating management traffic on a **dedicated VLAN** and restricting **VPN traffic to authorized channels only**, the design significantly reduces potential attack vectors.

The use of an **Admin Jumpbox** provides a controlled and audited interface for administrative tasks, further protecting critical internal resources such as **servers, Active Directory, and ISE systems**.

Overall, this architecture emphasizes **defense-in-depth**, combining:
- Network segmentation  
- Access control  
- Centralized monitoring  

to enhance organizational resilience against sophisticated cyber attacks.


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




