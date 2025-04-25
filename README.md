# TTS-Google-Music-restart 2025.04.25

-> Update : Add an automation and scripts example with Multi accounts and sources ! 

Restart music after Google announcement

Hello everyone ! I hope this helps you.

This repository allows you to add script launches to your Google Ads automations (e.g., doorbell announcement) to save and then replay the music in the state it was in before the ad (track played, volume, position).

You need to create two scripts that will be called in the TTS automation (If you have multiple sources you will need to create a save and restore script per device):

 - script_save_playing

 - script_restore_playing

After, add in automation script calls before and after sending TTS (with a delay) (like automation_example)


prerequisites: 

 - Spotcast last version (HACS)
   
 - Spotify premium

Enjoy

## DONATE

If you like it, please give my repo a star ✨

To buy me a coffee ☕️, or like beer 🍺, say only thanks 🙏, or another.

https://www.paypal.com/paypalme/romain13700

Thanks

