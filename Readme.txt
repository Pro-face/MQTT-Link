Ver 1.4
-Import/Export Configuration added

Ver 1.3

-Splash screen added
-more exception catches
-log improved
-Last will added to configuration
-Clean Session added to configuration
-not allowing multiple instances with this version
-string length column now shows 1 for all types other than string


Ver 1.2

-Log Screen scrolls better by showing scroll bars
-Log Screen autosorts to descending time by default so that new entries appear at top of list
-Changed handle creation and deletion location in code.
-Added TLS 1.0, 1.1, 1.2 support, cannot specify client or server certificate.  Server side only in this version.
-Previously port was always 1883 even if changed.  Can change port now.
-MQTT connected to server status(Connected, Not Connected) now shown in Notifyicon contextmenu.
-Log and configure windows show icons on taskbar
-log and configure windows cannot be resized
-added notifyicon tooltips for status of MQTT connection and service
-added context menu for status of broker connection
-added error catch for MQTT Broker not found
-Log window disables Contextmenu log link
-Added option for "Retain" to MQTT Publish

NOTE:  If you have installed and saved a previous configuration for MQTT Link, update each Publish line to make changes take effect.  Alertnatively delete data and log xml files in C:\Pro-face\MQTT LINK\ and restart MQTT Link.


Ver 1.1

-Added new icons for start, stop, application.
-Corrected exeception which may occur when exiting while service off.

Ver 1.0

Considerations:

-.net 4.6.1 required.  Setup.msi will automatically link to internet source for install if internet available.
- Runs at User level
- Windows 7, Windows 8, Windows 8.1, Windows 10 ready.
- After saving the configuration restart the service.

Limitations:

- no SSL/TLS in this version, hoping to add in 1.x
- logging interface may not refresh correctly on Windows 10.
