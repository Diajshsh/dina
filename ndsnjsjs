PKG=com.pubg.krmobile
am force-stop com.pubg.krmobile
am force-stop com.pubg.krmobile
am force-stop com.rekoo.pubgm
am force-stop com.vng.pubgmobile
PKG="com.pubg.krmobile"
data=/data/data/$PKG
eval `pm dump $PKG | grep LibraryDir`
lib=$legacyNativeLibraryDir
arm=$(ls $lib | grep arm)
lib=$lib/$arm
rm -rf $lib/{libCrashSight.so,libgamemaster.so,libigshare.so,libtgpa.so,libmmkv.so,libapp.so,libCrashSight.so,libc++_shared.so,libflutter.so,libgamemaster.so,libgcloudarch.so,libhelpshiftlistener.so,libigshare.so,libImSDK.so,libkk-image.so,liblbs.so,libmarsxlog.so,libmmkv.so,libnpps-jni.so,libsentry.so,libsentry-android.so,libsoundtouch.so,libst-engine.so,libtgpa.so,libtool-checker.so,libflutter_qapm.so};
printf "8192" > /proc/sys/fs/inotify/max_queued_events
printf "8192" > /proc/sys/fs/inotify/max_user_instances
printf "8192" > /proc/sys/fs/inotify/max_user_watches
iptables -I OUTPUT -p tcp -m string --string "www.anonymous.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "www.anonymous.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "gcloud.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "gcloud.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "googlesource.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "googlesource.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "android.googlesource.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "android.googlesource.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "dl.listdl.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "dl.listdl.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "crashsight.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "crashsight.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "crashsight.qq.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "crashsight.qq.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "www.wetest.net" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "www.wetest.net" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "qq.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "qq.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "tencent.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "tencent.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "anticheatexpert.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "anticheatexpert.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "cloud.vmp.onezapp.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "cloud.vmp.onezapp.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "dl.listdl.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "app.adjust.com" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "file-igamecj.akamaized.net" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "129.226.2.165" --algo bm -j DROP
iptables -I OUTPUT -p tcp -m string --string "dl.listdl.com" --algo bm -j DROP
iptables -I INPUT -p tcp -m string --string "dl.listdl.com" --algo bm -j DROP
iiptables -I INPUT -s dl.listdl.com -j DROP &>/dev/null;
iptables -I OUTPUT -s dl.listdl.com -j DROP &>/dev/null;
iptables -I OUTPUT -s lobby.igamecj.com -j DROP &>/dev/null;
iptables -I INPUT -s 61.151.168.203 -j DROP
iptables -I OUTPUT -s 61.151.168.203 -j DROP
iptables -I INPUT -s 76.223.65.111 -j DROP
iptables -I OUTPUT -s 76.223.65.111 -j DROP
iptables -I INPUT -p tcp --dport 80 -j REJECT
iptables -I OUTPUT -p tcp --dport 80 -j REJECT
iptables -I INPUT -p tcp --dport 80 -j DROP
iptables -I OUTPUT -p tcp --dport 80 -j DROP
iptables -I INPUT -p tcp --dport 20002 -j REJECT
iptables -I OUTPUT -p tcp --dport 20002 -j REJECT
iptables -I INPUT -p tcp --dport 20002 -j DROP
iptables -I OUTPUT -p tcp --dport 20002 -j DROP
iptables -I INPUT -p tcp --dport 8700 -j REJECT
iptables -I OUTPUT -p tcp --dport 8700 -j REJECT
iptables -I INPUT -p tcp --dport 8700 -j DROP
iptables -I OUTPUT -p tcp --dport 8700 -j DROP
iptables -I INPUT -p tcp --dport 8011 -j DROP
iptables -I OUTPUT -p tcp --dport 8011 -j DROP
iptables -I INPUT -p tcp --dport 10191 -j DROP
iptables -I OUTPUT -p tcp --dport 10191 -j DROP
iptables -I INPUT -p tcp --dport 10013 -j DROP
iptables -I OUTPUT -p tcp --dport 10013 -j DROP
iptables -I INPUT -p tcp --dport 8013 -j DROP
iptables -I OUTPUT -p tcp --dport 8013 -j DROP
iptables -I INPUT -p tcp --dport 20371 -j DROP
iptables -I OUTPUT -p tcp --dport 20371 -j DROP
iptables -I INPUT -p tcp --dport 9030 -j DROP
iptables -I OUTPUT -p tcp --dport 9030 -j DROP
iptables -I INPUT -p tcp --dport 8089 -j DROP
iptables -I OUTPUT -p tcp --dport 8089 -j DROP
iptables -I INPUT -p tcp --dport 9031 -j DROP
iptables -I OUTPUT -p tcp --dport 9031 -j DROP
iptables -I INPUT -p tcp --dport 15692 -j DROP
iptables -I OUTPUT -p tcp --dport 15692 -j DROP
echo ''128'' > /proc/sys/fs/inotify/max_user_instances
echo ''8192'' > /proc/sys/fs/inotify/max_user_watches
echo ''16384'' > /proc/sys/fs/inotify/max_queued_events
cd /proc/sys/fs/inotify && echo ''16384'' > max_queued_events
cd /proc/sys/fs/inotify && echo ''128'' > max_user_instances
cd /proc/sys/fs/inotify && echo ''8192'' > max_user_watches
pm disable com.pubg.krmobile/com.sirius.flutter.im.MeemoBGService  &>/dev/null;
pm disable com.pubg.krmobile/com.tencent.midas.oversea.newnetwork.service.APNetDetectService  &>/dev/null;
pm disable com.pubg.krmobile/com.sirius.meemo.foreground_service.ForegroundService &>/dev/null;
rm -rf $data/{app_bugly,app_crashrecord,app_crashSight}
touch $data/{app_bugly,app_crashrecord,app_crashSight}
chmod 000 $data/{app_bugly,app_crashrecord,app_crashSight}
rm -rf $data/files
chmod 755 $lib/*
rm -rf /data/media/0/Android/data/com.pubg.krmobile/files/TGPA
am start -n com.pubg.krmobile/com.epicgames.ue4.SplashActivity > /dev/null
while [ ! -e /data/media/0/Android/data/com.pubg.krmobile/files/TGPA ]
do sleep 1
done
sleep 3
chmod 000 $lib/libTDataMaster.so
chmod 000 $lib/libCrashSightCore.so
chmod 000 $lib/libUE4.so
chmod 000 $lib/libgcloud.so
chmod 000 $lib/libtprt.so
