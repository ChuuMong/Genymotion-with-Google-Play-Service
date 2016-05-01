# Genymotion-with-Google-Play-Service


Download the following ZIPs:
    
    ARM Translation Installer v1.1 (http://www.mirrorcreator.com/files/0ZIO8PME/Genymotion-ARM-Translation_v1.1.zip_links)
    
    Download the correct GApps for your Android version:
      Google Apps for Android 6.0 (https://www.androidfilehost.com/?fid=24052804347835438 - benzo-gapps-M-20151011-signed-chroma-r3.zip)
      Google Apps for Android 5.1 (https://www.androidfilehost.com/?fid=96042739161891406 - gapps-L-4-21-15.zip)
      Google Apps for Android 5.0 (https://www.androidfilehost.com/?fid=95784891001614559 - gapps-lp-20141109-signed.zip)
      Google Apps for Android 4.4.4 (https://www.androidfilehost.com/?fid=23501681358544845 - gapps-kk-20140606-signed.zip)
      Google Apps for Android 4.3 (https://www.androidfilehost.com/?fid=23060877490000124 - gapps-jb-20130813-signed.zip)
      Google Apps for Android 4.2 (https://www.androidfilehost.com/?fid=23060877490000128 - gapps-jb-20130812-signed.zip)
      Google Apps for Android 4.1 (https://www.androidfilehost.com/?fid=22979706399755082 - gapps-jb-20121011-signed.zip)
      Google Apps for Android 2.3.7 (http://www.mediafire.com/download/bs063kb0m742o5l/gapps-gb-20131027-signed.zip - gapps-gb-20131027-signe.zip)
  
Next Open your Genymotion VM and go to the Homescreen

Now Drag&Drop the Genymotion-ARM-Translation.zip onto the Genymotion VM window.

It should say "File transfer in progress", once it asks you to flash it click 'OK'

Now Reboot your VM using ADB. If nescessary you can simply close the VM window, not recommended

Once you're on the Homescreen again Drag&Drop the gapps-jb-20130813-signed.zip (or whatever version you got) onto your VM, and click 'OK' when asked

Once it finishes, again Reboot your VM and open the Google Play Store.

Sign in using your Google account

Once in the Store go to the 'My Apps' menu and let everything update (fixes a lot of issues), also try updating Google Play Services directly (https://play.google.com/store/apps/details?id=com.google.android.gms).
You can also search for Google Maps, update it manually (press update or install button) and you will receive the message to update Google Play Services
(For Android 4.4.4 and 5.0 is posible you need to reboot several times before updates are shown)

Now try searching for apps in Google Play and if you can find and install for example 'Netflix' or 'Google Drive' then congrats you now have ARM support and Google Play fully setup!
