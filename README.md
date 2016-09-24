# fontfconfig - fonts and fonts.conf

1. Replace */etc/fonts/fonts.conf*.
2. Copy *AdobeStd NotoSans NotoSansHans Tinos migu-1m seguisym* to */opt/fonts/core/*.
3. Usually this is ok.
   1. But you can `fc-cache -rf` to build all system fonts caches.
   2. You may restart X to take effect.
4. This setting works together with CJKTTY patch under Virtual Terminal.
5. Refer to [Jin Buguo](http://www.jinbuguo.com).
