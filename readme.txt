 Download file: https://www.tenable.com/downloads/nessus
 Đăng ký lấy Active Code
 Vào:  https://plugins.nessus.org/offline.php lấy plugin + key nessus
 sudo ./nessuscli update ~/Downloads/all-2.0.tar.gz
 copy file key vào /Library/Nessus/run/etc/nessus/nessus-fetch.rc (MACOS)
 restart etc/init.d/nessusd restart
 copy file plugin_feed_info.inc vào: /Library/Nessus/run/var/nessus & /Library/Nessus/run/lib/nessus/plugins
 sudo chown root:admin ./plugin_feed_info.inc && sudo chmod 644 ./plugin_feed_info.inc
