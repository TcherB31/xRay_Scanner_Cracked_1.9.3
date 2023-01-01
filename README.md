# xRay_Scanner_Cracked_1.9.3
xRay is a fairly powerful scanner that will allow you to scan and scout targets, as well as use yaml templates to scan vulnerabilities. Features that this scanner uses:

    1, the detection speed is fast. The hair bag is fast; the vulnerability detection algorithm is efficient.
    2, support wide. Big to OWASP TOP 10 universal vulnerability detection, small to various CMS frames POC can be supported.
    3, the code quality is high. The quality of the staff is high, and the code reliability is improved by multi-layer verification such as Code Review, unit test, integration test.
    4, advanced can be customized. Exposing the various parameters of the engine through the configuration file, by modifying the configuration files can be greatly customized.
    5, the security is not threatened. XRay is positioned as a secure assistance assessment tool, rather than attack tools, all of which PAYLOAD and POC are harmless checks.

![image](https://user-images.githubusercontent.com/108927927/193665253-a05ac9dd-95f7-45ee-acb1-c096a45a5d8e.png)

How to use scanner, all:

    ./xray webscan --basic-crawler http://example.com --html-output scan1.html

    ./xray webscan --url http://example.com/ ? a=b --html-output single-url.html

    ./xray webscan --plugins cmd-injection,sqldet --url http://example.com

    ./xray webscan --url http://example.com/ ? a=b \
    --text-output result.txt --json-output result.json --html-output report1.html

You can also use the tool to generate your own PoC template, it is also about the web interface. Convenient to use! Link --> https://phith0n.github.io/xray-poc-generation/
![image](https://user-images.githubusercontent.com/108927927/193665292-5b4482f5-e817-4d4b-ba62-781e3b55bdb3.png)
I attach a link to (working crack ), as well as examples of reports on the scan, so that they would have an idea of scanning
![image](https://user-images.githubusercontent.com/108927927/193665346-5102308b-4c79-4a72-9fdc-5f10316c64e6.png)
