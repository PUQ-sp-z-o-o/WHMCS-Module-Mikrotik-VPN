# Product Configuration in WHMCS

#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-mikrotik-vpn) | [Dowload](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/) | [FAQ](https://faq.puqcloud.com/)

##### Add new product to WHMCS

```
System Settings->Products/Services->Create a New Product
```

In the **Module settings** section, select the **"PUQ mikrotik VPN"** module

[![image-1672836812135.png](https://doc.puq.info/uploads/images/gallery/2023-01/scaled-1680-/image-1672836812135.png)](https://doc.puq.info/uploads/images/gallery/2023-01/image-1672836812135.png)

- **License key:** A pre-purchased license key for the **"PUQ Mikrotik VPN"** module. For the module to work correctly, the key must be active
- **Comment PREFIX:** The prefix that will be added to the VPN user's comment on the Mikrotik router
- **Profile:** PPP secret profile on mikrotik router
- **Service:** A service that will be available to a VPN user on a Mikrotik router
- **Bandwidth Download:** Download Bandwidth Limit in M/s
- **Bandwidth Upload:** Upload Bandwidth Limit M/s
- **Traffic One Time/Monthly in GB/Traffic Quarterly in GB/Traffic Semi-Annually in GB/Traffic Annually in GB/Traffic Biennially in GB/Traffic Triennially in GB :** Packet traffic that will be added to the balance every billing period, respectively
- **Save traffic history (days):** The number of days it takes to save user traffic usage statistics
- **User notification traffic limit email template:** The template of the letter that will be sent to the client if the remaining traffic is less than XXX
- **Notification traffic remainder less than X GB:** The amount of traffic on the client's balance below which a notification will be sent.
- **Suspend exceeding traffic limit email template:** The template of the letter that will be sent to the client if his traffic balance is 0 or less 0
- **Link to instruction:** Link to the instruction, if filled out, it will be reflected in the client area
- **Support PPtP/Support L2TP:** If checked, it will be reflected in the client zone
- **L2TP IPSec PSK key:** it will be reflected in the client zone
- **Statistics collection frequency :** The frequency with which traffic usage statistics will be collected. It also checks the positive balance and if the traffic balance is exhausted, it disables the vpn account on the Mikrotik server.