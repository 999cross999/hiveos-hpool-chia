
<h1><img class="icon" src="https://www.chia.net/wp-content/uploads/2023/01/chia-logo-dark.svg" width="120"> OG/PP HPOOL miner+plotter for HiveOS<img src="!https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ757CjA-Zt6ltQK4gp-Abbm3-j3-Mw3xQZkA&usqp=CAU" width="150"></h1>
<img src="https://github.com/999cross999/hiveos-hpool-chia/raw/main/pictures/screenshot-plot.png" width="1200">
<h3>For any questions / bugs, write to me!</h3>
<h3> My contacts: Telegram @cross964008, Email: 999cross999@gmail.com</h3>
<p><b> MINER v2.0.1: </b>https://github.com/999cross999/hiveos-hpool-chia/releases/download/2.0.2/hiveos-hpool-chia-2.0.2-2.0.2_stable.tar.gz</p>
<p><b>HDD must be NTFS file system and named CHIAOG*** or CHIAPP***!</b></p>
<p><b>Instead of *** there should be a disk number, for example: CHIAOG001, CHIAOG002 or CHIAPP001, CHIAPP002</b></p>
<p><b>SSD for plotting must be named CHIASSD (if you didn't specify a custom name in the external_ssd_name argument)</b></p>
<p><b>Plotter + Miner requirements: HiveOS, 4 Cores, 16GB RAM, SSD/HDD ≥ 360 GB to create plots</b></p>
<p><b>Miner Requirements: HiveOS, 2 Cores, 4GB RAM</b></h4>
<h2>1. Copy your API key from hpool.in </h2>
<img src="https://github.com/999cross999/hiveos-hpool-chia/blob/main/pictures/screenshot-2.png">
<h2>2. Create an XCH wallet, enter your API key in the "Address line" </h2>
<img src="https://github.com/999cross999/hiveos-hpool-chia/blob/main/pictures/screenshot-3.png">
<h2>3. Create a flight sheet like in this screenshot </h2>
<img src="https://github.com/999cross999/hiveos-hpool-chia/blob/main/pictures/screenshot-4.png">
<h2>4. In the Setup Miner Config menu, specify the settings as in the screenshot </h2>
<h4>For OG or PP version you need to use api key and hpool server</h4>
<h4>"Address line" example: APIKEYOG or APIKEYPP</h4>
<h4>"pool URL" example: jp (for OG) or eu (for PP)</h4>
<img src="https://github.com/999cross999/hiveos-hpool-chia/blob/main/pictures/screenshot-5.png">
<p><b> MINER v2.0.1: </b>https://github.com/999cross999/hiveos-hpool-chia/releases/download/2.0.2/hiveos-hpool-chia-2.0.2-2.0.2_stable.tar.gz</p>
<p><b>Use the arguments in "Extra config arguments":</b></p>
<p><b>miner_mode_og: enable </b><- Enable OG miner (allowed to be used in conjunction with PP miner)</p>
<p><b>miner_mode_pp: enable </b><- Enable PP miner (allowed to be used in conjunction with OG miner)</p>
<p><b>xproxy_service_og: enable </b><- Enable OG xproxy (allowed to be used in conjunction with PP xproxy, port 9190)</p>
<p><b>xproxy_service_pp: enable </b><- Enable PP xproxy (allowed to be used in conjunction with OG xproxy, port 9191)</p>
<p><b>xproxy_og_url: </b><- Miner OG xproxy address (If not specified, it is used http://localhost:9190/ with xproxy_service_og: enabled) </p>
<p><b>xproxy_pp_url: </b><- Miner PP xproxy address (If not specified, it is used http://localhost:9191/ with xproxy_service_pp: enabled) </p>
<p><b>plotter_mode_og: enable </b><- Enable OG chia_plot (Cannot be used with PP chia_plot)</p>
<p><b>plotter_mode_pp: enable </b><- Enable PP chia_plot (Cannot be used with OG chia_plot)</p>
<p><b>farmer_public_key: key </b><- Your Farmer Public Key must be 96 chars long(For OG&PP)</p>
<p><b>pool_public_key: key </b><- Your Pool Public Key must be 96 chars long(For OG)</p>
<p><b>pool_contract_address: key </b><- Your Pool Contract Address must be 62 chars long (For PP)</p>
<p><b>use_internal_ssd: enable </b><- Use SSD on which HiveOS is installed (Must be 360 GB!)</p>
<p><b>external_ssd_name: SSD name </b><- External SSD Name (Default CHIASSD)</p>
<p><b>max_temp_hdd: 60 </b><- Maximum HDD temperature (Protection is disabled by default)</p>
<p><b>You can select the hpool server in the "pool URL" line:</b></p>
<p><b>HPOOL CHIA OG:</b> (cn = China, hk = Hongkong, jp = Japan)</p>
<p><b>HPOOL CHIA PP:</b> (cn = China, na = Americas, eu = Europe, me = Middle East)</p>
<h4>For the OG + PP version, you need to use two api keys, two hpool servers through a dot</h4>
<h4>"Address line" example: APIKEYOG.APIKEYPP</h4>
<h4>"pool URL" example: jp.eu</h4>
<img src="https://github.com/999cross999/hiveos-hpool-chia/blob/main/pictures/screenshot-6.png">
<h1>Enjoy mining and plotting CHIA on HiveOS! </h1>
<h3>To support the project, you can send cryptocurrency:</h3>
<h3><img src="https://s2.coinmarketcap.com/static/img/coins/64x64/1.png" width="32"> 1FGwu22Tp7nnkUqLUn74exKpBy73qDYT5D</h3>
<h3><img src="https://s2.coinmarketcap.com/static/img/coins/64x64/9258.png" width="32"> xch1p7cjvm77xan47w8xd7z432z8h0aj45szdt6caml3sjwjzjn8646q857l5j</h3>
<h3><img src="https://s2.coinmarketcap.com/static/img/coins/64x64/825.png" width="32"> TNqKwGFtDYDHYYNfb2NBAqeyo6QFUzhL3W</h3>
<h3>For any questions / bugs, write to me. My contacts:</h3>
<h3>Telegram @cross964008, Email: 999cross999@gmail.com</h3>
<h2>P.S.</h2>
<h4>DevFee: One core of your CPU mines for developer, but it gives me an incentive to develop the project further. This does not affect the plotting/mining process in any way</h4>
<p><b>This project was written by trial and error. HiveOS refused to answer my questions.</b></p>
<p><b>Thanks HiveOS for the "support"! This gift for HiveOS:</b></p>
<img src="https://github.com/999cross999/hiveos-hpool-chia/blob/main/pictures/for-hiveos.png">
