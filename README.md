# Detect CVE

Tool that detect CVE of website

## Requirements

* Python 2.7 or Python 3.4+
* Works on Linux, Windows

## Detect CVE of Drupal sites
### CVE 2018 - 7600 (Drupalgeddon) + CVE 2019 - 6340

With input file (drupal sites with version) 

```
...
autocraft-kzn.ru|5
bergerault.com|5
leisureandculturedundee.com|5
...
```

Return normal site and vulnerable site (mark as |VULNERABLE|...) or other cases

```
...
viadux.com.au|8.xx|Redirected|
haapajarvi.fi|8.xx|cleanURL_enable|
esd.ornl.gov|8.xx|N/A|
factsonhand.com|8.3.1|VULNERABLE|
...
```

run with command format like: 
> $ python Scan.py [inputFile] [outputFile] [option]

In case want to detect CVE-2018-7600:

```
$ python Scan.py \input\input_1.txt output_1.txt 2018
...
```
OR CVE-2019-6340
```
$ python Scan.py \input\input_1.txt output_1.txt 2019
...
```

---

## Built With

* [Python2.7](https://docs.python.org/2.7/)
* [Python3.6](https://docs.python.org/2.6/)

## Version

> Draft 
* include all pervious version that incomplete or unresolve bugs 

> Source_Final 
* release version

## Authors
### BB01 team
