ModernCalendarPlus
==================

Pebble Watchface combining ModernMinimal with ModernCalendar.
The end result is an analog watchface with clean minimal design, which presents calendar events read from Smartwatch Pro.

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/IL/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>


ModernCalendar Plus is an integration by ShaBP of two separate watchfaces:
  Modern Minimal by JWay5929
  ModernCalendar by Fowler/Baeumle, which works with Baeumle's popular Smartwatch Pro
Both of those watchfaces are based on the popular Modern watchface by Lukasz Zalewski

Like Modern Minimal - shake to see battery and bluetooth connection status, but also added week of year and status of the connection with Smartwatch Pro. The coming (or current) event is written at the bottom. When there's no event in the near future, nothing is presented to keep the clean minimal look.



