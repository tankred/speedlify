# Notes

10 . [speedlify](https://github.com/zachleat/speedlify) (site performance benchmarking tool)
15 . clone repo to local machine - DONE
20. Run locally /linter/speedlify - ? 
30. Deploy to: staging >> https://staging.vives.be/speedlify/sample/ - NOK
50. [The Ultimate Guide to Web Performance](https://dev.to/ender_minyard/the-ultimate-guide-to-web-performance-ci4)

## Lighthouse 

[run lighthouse 7 ♦](https://github.com/GoogleChrome/lighthouse)

Update lighthouse
```
npm i -g lighthouse
```

```
   lighthouse https://web.vives.be/stuvodossiers/ --port 57163
```

```
   lighthouse https://web.vives.be/stuvodossiers/Student/Zoek?search=xcl --port 57163 --disable-device-emulation --disable-cpu-throttling --disable-network-throttling
```
```
lighthouse --help
```

? chrome-debug

--perf 1  #   Use a performance-test-only configuration    [boolean]

```
PS C:\tmp\log> lighthouse https://web.vives.be/stuvodossiers/PsychoSociaal/Overzicht?studentId=3139 --port 60452 --disable-device-emulation --disable-cpu-throttling --disable-network-throttling --perf 1 --output-path=web.vives.be_psy_overzicht3139_20170829.html
```

### TARGET  

* VerlofApp
* stem4math.eu
* webshop
* [webshop login](https://web.vives.be/webshop/Account/Login?ReturnUrl=%2Fwebshop%2F)

collect data on Responsive Performance: do not test your responsive designs only in the comfort of your own office, on your high-speed connection.

## Hat tip

* Heroku vs Openshift (Red hat) 
* Compare netlify to X Y Z
* [netlify vs heroku](https://startuptalky.com/netlify-vs-heroku/) vs vercel
* heroku wins
* [netlify (static web hosting)](https://app.netlify.com/signup) 

