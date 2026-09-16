# Bug Bounty Dorks

A curated collection of search-engine queries for discovering **public bug bounty programs, Vulnerability Disclosure Programs (VDPs), responsible disclosure policies, `security.txt` files, security contacts, rewards, swag, and researcher Hall of Fame pages.**

This project is intended as a reference for security researchers performing **authorized reconnaissance and vulnerability disclosure research**.

---

## Repository Structure

```text
bug-bounty-dorks/
│
├── README.md
├── LICENSE
│
├── dorks/
│   ├── general.txt
│   ├── security-txt.txt
│   ├── responsible-disclosure.txt
│   ├── bug-bounty.txt
│   ├── rewards.txt
│   ├── swag.txt
│   ├── hall-of-fame.txt
│   ├── platforms.txt
│   ├── universities.txt
│   ├── government.txt
│   └── country-specific.txt
│
└── templates/
    └── findings-notes.md
```

---

# Categories

| File                         | Description                                                  |
| ---------------------------- | ------------------------------------------------------------ |
| `general.txt`                | General security and vulnerability-reporting searches        |
| `security-txt.txt`           | Searches for `security.txt` and security contact information |
| `responsible-disclosure.txt` | Responsible disclosure policies                              |
| `bug-bounty.txt`             | Public bug bounty programs                                   |
| `rewards.txt`                | Monetary rewards, bounty and compensation searches           |
| `swag.txt`                   | Swag and researcher recognition                              |
| `hall-of-fame.txt`           | Security researcher Hall of Fame pages                       |
| `platforms.txt`              | Bug bounty platforms and program providers                   |
| `universities.txt`           | University security programs and disclosure policies         |
| `government.txt`             | Government security and vulnerability disclosure programs    |
| `country-specific.txt`       | Country and regional searches                                |

---

# Example Searches

### Security Pages

```text
inurl:/security
inurl:"security report"
inurl:reporting-security-issues
intext:"submit vulnerability report"
intext:"we take security very seriously"
```

### Security.txt

```text
inurl:security.txt
inurl:/.well-known/security.txt
inurl:/security.txt "contact"
"security.txt" AND ("mailto" OR "contact")
```

### Responsible Disclosure

```text
inurl:/responsible-disclosure
inurl:responsible-disclosure-policy
"responsible disclosure" reward
"responsible disclosure" bounty
```

### Bug Bounty

```text
inurl:"bug bounty"
inurl:bug-bounty
inurl:bugbounty
intext:bounty inurl:/security
"we run a bug bounty program"
```

### Rewards

```text
inurl:"bug bounty" intext:"$"
inurl:"bug bounty" intext:"€"
inurl:bug-bounty intext:"₹"
intext:"eligible for a reward"
intext:"monetary compensation"
```

### Researcher Recognition

```text
"responsible disclosure" "hall of fame"
"security hall of fame"
"security researcher" swag
"If you discover a vulnerability" swag
```

---

# Regional Research

The collection also contains regional searches for security disclosure programs, including:

* 🇳🇱 Netherlands
* 🇬🇧 United Kingdom
* 🇪🇺 European Union
* 🇩🇪 Germany
* 🇫🇷 France
* 🇮🇹 Italy
* 🇨🇭 Switzerland
* 🇦🇹 Austria
* 🇧🇪 Belgium
* 🇸🇪 Sweden
* 🇩🇰 Denmark
* 🇳🇴 Norway
* 🇵🇱 Poland
* 🇪🇸 Spain
* 🇯🇵 Japan
* 🇨🇦 Canada
* 🇦🇺 Australia
* 🇧🇷 Brazil
* 🇮🇳 India

See [`dorks/country-specific.txt`](d)
