---
title: 'Back to Basic Linux'
description: 'Cheatsheet and notes on Linux back to basic'
pubDate: 'May 7 2025'
heroImage: '/blog-placeholder-1.jpg'
---

# Back to Basic Linux

## Shell Variables and Echo
```bash
name="VArtz"
echo $name
bankname="WorldBanc"
founded="1969"
ceo="Jeff Gates"
echo "$bankname was founded in $founded by $ceo"
department="Engineering"
team="ops"
echo "I work in $department on $team"
```

## File Operations
```bash
# Download and extract WorldBanc repository
curl -L https://github.com/bootdotdev/worldbanc/archive/refs/heads/main.zip -o worldbanc.zip
unzip worldbanc.zip
rm worldbanc.zip
mv worldbanc-main worldbanc
sudo chown -R $(whoami) worldbanc
sudo chmod -R 755 worldbanc

# Navigate and explore files
cd worldbanc/
ls public/
cat public/pr_ideas.txt
cd private/transactions/
head -n 6 2023.csv
```

## File Management
```bash
# Create and remove directories
touch credithistory.txt
mkdir my_directory
rm -r my_directory/

# Move files between directories
mkdir investments
mv credit_cards/tbills.txt investments

# Remove sensitive files
rm -r passwords/
```

## System Administration
```bash
# File permissions
chmod -R u=rwx,g=,o= .
chmod u+x genids.sh

# Change ownership
sudo chown -R root contacts

# Search files
grep "CRITICAL" 2024-01-10.log
grep -r "CRITICAL" .
find . -name "*joint*"
```

## Installing Tools
```bash
# Install lsd (modern ls replacement)
curl -sS https://webi.sh/lsd | sh
source ~/.config/envman/PATH.env

# Use lsd for better directory listing
lsd --tree
lsd --tree --classic
```

## Company Information
```markdown
# Company Info

* Company Name: Worldbanc Inc.
* Company Address: 1234 Main St, New York, NY 10001
* Company Phone: 212-555-1212
* Company Email: worldbanc@example.com
* Company Password: REDACTED
```

## PR Ideas (Excerpt)
```
WorldBanc will plant a tree for every new account opened.
But here's the twist - each tree will be adorned with fake dollar bills featuring the CEO's face.
Customers can come and 'harvest' the faux cash from their personal trees, exchanging it for real money at a hilariously low exchange rate.

WorldBanc Cares: Recognizing the importance of personal touch in the digital age,
we introduce a new campaign where the CEO personally writes an email to every customer Mr. Beast style.
To top it off, each email signs off with a digitally autographed photo of the CEO giving a thumbs up.

The WorldBanc Blimp Bonanza: The best way to stay 'above' the competition is quite literal - by investing in a fleet of blimps.
These blimps, emblazoned with the WorldBanc logo, will hover over major cities, occasionally dropping WorldBanc-branded swag.
The pièce de résistance? Each blimp plays a jingle, the lyrics of which are just the company's stock ticker symbol repeated to a catchy tune.
```
