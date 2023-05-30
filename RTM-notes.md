# RTM notes

Heroku vs Openshift (Red hat) 
Compare netlify to X Y Z
[netlify vs heroku](https://startuptalky.com/netlify-vs-heroku/) vs vercel
heroku wins
[netlify](https://app.netlify.com/signup) = static web hosting


10 . speedlify STAGING
15 . clone repo to local machine
 20. Run locally /linter/speedlify
 30. Deploy to: staging >> https://staging.vives.be/speedlify/sample/ NOK
>> 40. Deploy to Netlify 
 500. [The Ultimate Guide to Web Performance](https://dev.to/ender_minyard/the-ultimate-guide-to-web-performance-ci4)

[run lighthouse 7 ♦](https://github.com/GoogleChrome/lighthouse)
TARGET : 
* VerlofApp
* stem4math.eu
* webshop

collect data on Responsive Performance: do not test your responsive designs only in the comfort of your own office, on your high-speed connection.

+ create cheat sheet 
++ for easy copy: cat readme.md
? how to login, and avoid page redirection ! 
+ run perf. only:
--perf 1  #   Use a performance-test-only configuration    [boolean]

## MAN

lighthouse --help
chrome-debug
PS C:\tmp\log> lighthouse https://web.vives.be/stuvodossiers/PsychoSociaal/Overzicht?studentId=3139 --port 60452 --disable-device-emulation --disable-cpu-throttling --disable-network-throttling --perf 1 --output-path=web.vives.be_psy_overzicht3139_20170829.html

[webshop login](https://web.vives.be/webshop/Account/Login?ReturnUrl=%2Fwebshop%2F)

## LOG 

20180222; npm i -g lighthouse # update to 2.9.1

## DATA

20171103; http://navorming.vives.education/; Perceptual Speed Index: 6,756

* DATE;   <project>; (ggl alert) 
Oct 23, 2017 	WEBSHOP-loadtime-MORE-than-3-s
Oct 22, 2017    WEBSHOP-loadtime-MORE-than-3-s
Oct 13, 2017    WEBSHOP-loadtime-MORE-than-3-s
Oct 5, 2017     WEBSHOP-loadtime-MORE-than-3-s
Sep 29, 2017    WEBSHOP-loadtime-MORE-than-3-s
Nov 10, 2017    WEBSHOP-loadtime-MORE-than-3-s 
Nov 24, 2017 	WEBSHOP-loadtime-MORE-than-3-s 
Nov 27, 2017 	WEBSHOP-loadtime-MORE-than-3-s 
Dec 4, 2017 	WEBSHOP-loadtime-MORE-than-3-s 
Dec 5, 2017 	WEBSHOP-loadtime-MORE-than-3-s 
Dec 13, 2017 	WEBSHOP-loadtime-MORE-than-3-s 
Oct 17, 2017    EVK-loadtime-MORE-than-3-s
Nov 6, 2017     EVK-loadtime-MORE-than-3-s

## DONE

 Id CommandLine
  -- -----------
   1 cd \tmp
   2 lighthouse https://web.vives.be/stuvodossiers/ --port 57163
   3 ls *light*
   5 lighthouse https://web.vives.be/stuvodossiers/Student/Zoek?search=xcl --port 57163 --disable-device-emulation --disable-cpu-throttling --disable-network-throttling
   6 ./web.vives.be_2017-08-28_13-44-40.report.html
   7 vi config.json
