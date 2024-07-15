# Android-Forensics-Cheatsheet
Android forensic artifacts cheat sheet :

.\data\system\users\%USERNUMBER%\settings_secure.xml	-	Android ID, Bluetooth name, Bluetooth address
..\data\system\usagestats\%USERNUMBER%\version	-	OS version, Build codename, Build version
..\data\drm\pvt\ahrh	-	IMEI
..\data\user_de\%USERNUMBER%\com.android.providers.telephony\databases\telephony.db	-	Display name, ICCID, IMSI, Country (SIM card details)
..\data\misc\bootstat\factory_reset	-	Factory reset time (UTC)
..\data\misc\bootstat\last_boot_time_utc	-	Last boot time (UTC)
..\data\misc\adb\adb_keys.	-	host connects to the device through adb.

..\data\system_ce\%USERNUMBER%\accounts_ce.db
..\data\system_de\%USERNUMBER%\accounts_de.db	-	users’ application account details, including login credentials, account IDs, authentication tokens, and more
..\data\user\%USERNUMBER%\com.google.android.apps.turbo\shared_prefs\app_usage_stats.xml	-	hardware and software usage statistics.
.\data\data\com.google.android.apps.wellbeing\databases\app_usage
Samsung : ..\data\data\com.samsung.android.forest\databases\dwbCommon.db	-	Digital Wellbeing service that collects usage statistic
.\data\data\com.android.vending\databases\frosting.db	-	application is installed or updated
..\data\data\com.android.vending\databases\suggestions.db	-	Google Play Store searches
..\data\data\com.WhatsApp\databases\msgstore.db	-	WhatsApp stores account data
..\data\data\com.WhatsApp\files	-	WhatsApp encrypts and decrypts database backups with a key
..\Android\media\com.whatsapp\WhatsApp\Media.	-	WhatsApp Media files

/data/datacom.instagram.android/shared_prefs/com.instagram.android_preferences.xml	-	Instagram -User ID,Username,account type,user account accesstime, biography, profile photo
/data/datacom.instagram.android/shared_prefs/<id account>_userBootstrapService.xml	-	Instagrams followers,following,
close friends list
	
	


