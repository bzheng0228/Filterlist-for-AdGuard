# Filterlist for AdGuard 2.50 🖥💟🛡

💚 This repo is actively maintained and updates about twice per day

![Logo](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/Logo_AG.png)

VITAL NEWS (31 Jan 2021): I'm having to use a stop-gap solution in regards to the filesize limit on GitHub.

BE SURE TO UPDATE THE ITEMS IN ADGUARD HOME.

My temporary solution is to split the blocklist text file into two:

* https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist1.txt
* https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist2.txt

I'll try to come up with a better solution within the next few days.

## About ℹ

A very aggressive filter-list that consolidates over __310 lists__ for use in
AdGuard Home (https://github.com/AdguardTeam/AdguardHome).

* Includes the AdGuard's official **AdGuardSDNSFilter**
* Is cleaned, sorted, with duplicates removed

### VITAL NOTES 👀

* Check that your added lists match the two links below (changed 31 Jan 2021)
* Please learn AdGuard Home's interface before using this list
* The list is very aggressive so before using this list please ensure that you add your own
"Custom filtering rules" for domains you want to allow
e.g: `@@||nexusmods.com^$important`
* Since everyone uses the internet differently please be aware that some initial
manual whitelisting is required
* The blocklist is around 120MB so if you're internet plan is data limited please account for
about 3000MB (3GB) per month, if AdGuard Home is set to update once per day
* The list is more cleaned up, optimized and better than ever

It's a BIG change so please report any false positives for domains.

### What it Blocks 👁‍

* advertisements, affiliates and analytics
* botnets, crypto-lockers and data miners
* drug sales, enrichments and fake sites
* fake news, invasive telemetry and phishing sites
* ransomware websites, scam and shock sites
* social media junk, spam and suspicious sites
* trackers, typosquatting, some CDNs and widgets

## Usage 📐

For more information view the [wiki](https://github.com/hl2guide/Filterlist-for-AdGuard/wiki).

Check that you are using __AdGuard Home v0.104.3__ or later
(vital functionality was hotfixed).

Once you have __AdGuard Home__ ready and are logged in, use its main menu to add
one __blocklist__ and one __allowlist__.

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/example%20menu.PNG "Menu")

### Blocklist 🛑

* https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist1.txt
* https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Blocklist/filter_blocklist2.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/blocklist.JPG "Blocklist")

### Allowlist ✅

https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_whitelist.txt

![menu](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/Screenshots/allowlist.JPG "Whitelist")

### Filters Update Interval ⏱

You can modify how often filter lists are updated within Adguard Home in the
__Settings__ > __General Settings__ page.

Set "Filters update interval" to 12 hours _(recommended)_ and click the green "Save" button.
This list updates around twice per day.

## Credits ☺️

Full credit for the actual blocking ability goes to original list creators and maintainers.

Thanks so much for their tireless work! :D

## Filter Lists 🗂️

The included lists are listed
[here](https://raw.githubusercontent.com/hl2guide/Filterlist-for-AdGuard/master/filter_list_URLs.txt).
