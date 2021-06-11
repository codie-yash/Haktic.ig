
<p align="center">
</p>
<p align="center"><img src="https://img.shields.io/badge/Version-1.0-brightgreen"></p>
<p align="center">
  <a href="https://github.com/codie-yash">
    <img src="https://img.shields.io/github/followers/codie-yash?label=Follow&style=social">
  </a>
  <a href="https://github.com/codie-yash/osi.ig/stargazers">
    <img src="https://img.shields.io/github/stars/codie-yash/Haktic.ig?style=social">
  </a>
</p>
<p align="center">
  Open Source Information Instagram
</p>

---

* The Hacktic OSINT Tool gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

* The information includes:

* [ profile ] : user id, followers / following, number of uploads, profile img URL, business enum, external URL, joined Recently, etc

* [ tags & mentions ] : most used hashtags and mentioned accounts

* [ email ] : if any email is used any where it'll be displayed

* [ posts ] : accessability caption, location, timestamp, caption, picture url, etc
  * ( yet not working correctly with posts instagram marks as 'sensitive cotent' )  

---

## • How To Install

$ pkg install -y git

$ git clone https://github.com/codie-yash/Haktic.ig.git && cd Haktic.ig

$ python3 -m pip install -r requirements.txt

## • Usage

$ python3 main.py -u username

$ python3 main.py -h

-p, --post images info highlight


## • Update

$ git pull

---

