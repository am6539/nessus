 Download file: https://www.tenable.com/downloads/nessus
 Đăng ký lấy Active Code
 Vào:  https://plugins.nessus.org/offline.php lấy plugin + key nessus
 sudo ./nessuscli update ~/Downloads/all-2.0.tar.gz
 copy file key vào /Library/Nessus/run/etc/nessus/nessus-fetch.rc (MACOS)
 restart etc/init.d/nessusd restart
 copy file plugin_feed_info.inc vào: /Library/Nessus/run/var/nessus & /Library/Nessus/run/lib/nessus/plugins
 sudo chown root:admin ./plugin_feed_info.inc && sudo chmod 644 ./plugin_feed_info.inc



Linux như trên:

 1. Download file: https://www.tenable.com/downloads/nessus
 2. Đăng ký lấy Active Code: https://zh-cn.tenable.com/products/nessus/nessus-essentials
 3. Vào:  https://plugins.nessus.org/offline.php lấy plugin + key nessus
 https://drive.google.com/file/d/1ut7zHrupOAdLFhpYRXGzHTrSW7VScQBS/view?usp=sharing
 4. sudo /opt/nessus/sbin/nessuscli update all-2.0.tar.gz
 5. copy file plugin_feed_info.inc vào /opt/nessus/lib/nessus/plugins/plugin_feed_info.inc và opt/nessus/var/nessus/plugin_feed_info.inc
 6. chmod readonly 2 file .inc
 7. restart nessus
