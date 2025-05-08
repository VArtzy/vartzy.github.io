  489  name="VArtz"
  490  echo $name
  491  bankname="WorldBanc"
  492  founded="1969"
  493  ceo="Jeff Gates"
  494  echo "$bankname was founded in $founded by $ceo"
  495  department="Engineering"
  496  team="ops"
  497  echo "I work in $department on $team"
  498  history
  499  clear
  500  exit
  501  curl -L https://github.com/bootdotdev/worldbanc/archive/refs/heads/main.zip -o worldbanc.zip
  502  unzip worldbanc.zip
  503  rm worldbanc.zip
  504  mv worldbanc-main worldbanc
  505  sudo chown -R $(whoami) worldbanc
  506  ls
  507  curl -L https://github.com/bootdotdev/worldbanc/archive/refs/heads/main.zip -o worldbanc.zip
  508  ls
  509  unzip worldbanc.zip
  510  apt install unzip
  511  unzip worldbanc.zip
  512  ls
  513  rm worldbanc.zip
  514  mv worldbanc-main worldbanc
  515  ls
  516  sudo chown -R $(whoami) worldbanc
  517  sudo chmod -R 755 worldbanc
  518  ls
  519  cd worldbanc/
  520  ks
  521  ls
  522  cd ..
  523  ls worldbanc/
  524  cd worldbanc/
  525  ls
  526  cd public/
  527  cat pr_ideas.txt
  528  cd ..
  529  cd private/transactions/
  530  cat 2023.csv
  531  head -n 6 2023.csv
  532  head -n 6 2023.csv | tail -n 5 2023.csv
  533  WorldBanc will plant a tree for every new account opened.
  534  But here's the twist – each tree will be adorned with fake dollar bills featuring the CEO's face.    
  535  Customers can come and 'harvest' the faux cash from their personal trees, exchanging it for real mone
y at a
  536  hilariously low exchange rate.
  537  WorldBanc Cares: Recognizing the importance of personal touch in the digital age,
  538  we introduce a new campaign where the CEO personally writes an email to every customer Mr. Beast styl
e.
  539  To top it off, each email signs off with a digitally autographed photo of the CEO giving a thumbs up.

  540  The WorldBanc Blimp Bonanza: The best way to stay 'above' the competition is quite literal – by inves
ting in
  541   a fleet of blimps.
  542  These blimps, emblazoned with the WorldBanc logo, will hover over major cities, occasionally dropping
 WorldB
  543  anc-branded swag like pens, notepads, and stress balls.
  544  The pièce de résistance? Each blimp plays a jingle, the lyrics of which are just the company's stock 
ticker

symbol repeated to a catchy tune.


  545  less 2023.csv
  546  less -N 2023.csv
  547  less -N 2023.csv
  548  cd ../../
  549  cd public/products/credit_cards/
  550  touch credithistory.txt
  551  ls
  552  mkdir my_directory
  553  rm my_directory/
  554  rm -r my_directory/
  555  ls
  556  cd ../
  557  mkdir investments
  558  ls
  559  mv credit_cards/tbills.txt investments
  560  cd investments/
  561  ls
  562  cd ../../../
  563  cd private/
  564  cat passwords/passwords.txt
  565  ls
  566  ls passwords/
  567  rm -r passwords
  568  ls
  569  cd transactions/
  570  cd backups/
  571  ls
  572  cd ../
  573  ls
  574  ls backups/
  575  cp 2020.csv backups
  576  cd backups/
  577  ls
  578  cd ../../
  579  cd logs/
  580  grep "CRITICAL" 2024-01-10.log
  581  grep -r "CRITICAL" .
  582  ls
  583  cd ../../../
  584  cd worldbanc/public/products/
  585  find . -name "joint"
  586  ls
  587  ls
  588  find . -name "*joint*"
  589  whoami
  590  sudo whoami
  591  cd ../../private/
  592  ls -l
  593  chmod -R u=rwx,g=,o= .
  594  ls -l
  595  cd bin
  596  chmod -x genids.sh
  597  ./genids.sh
  598  chmod u+x genids.sh
  599  ./genids.sh
  600  cd ../
  601  ls
  602  ls contacts/
  603  cat contacts/emergency.txt
  604  sudo chown -R root contacts
  605  ls -l
  606  rm -r contacts/
  607  ls
  608  history
root@main:~/worldbanc/private# stress coy
semoga cepet move on

Run :checkhealth for more info
root@main:~/worldbanc/private/bin# cd ../../public/
root@main:~/worldbanc/public# nvim company_info.md
root@main:~/worldbanc/public# cat company_info.md
# Company Info

* Company Name: Worldbanc Inc.
* Company Address: 1234 Main St, New York, NY 10001
* Company Phone: 212-555-1212
* Company Email: worldbanc@example.com
* Company Password: REDACTED
root@main:~/worldbanc/public# which nvim
/usr/bin/nvim
root@main:~/worldbanc/public# curl -sS https://webi.sh/lsd | sh; \
> source ~/.config/envman/PATH.env


>>> Welcome to Webi! - modern tools, instant installs.  <<<
    We expect your experience to be absolutely perfect!

    Success? Star it!   https://github.com/webinstall/webi-installers
    Problem? Report it: https://github.com/webinstall/webi-installers/issues
                        (your system is GNU/Linux/x86_64 with libc & curl+wget)

Bootstrapping Webi
    Downloading https://webi.sh/packages/webi/webi.sh
        to ~/.local/bin/webi
    Running ~/.local/bin/webi lsd@stable

Installing lsd ...
    Found  ~/.local/bin
    Initializing ~/.config/envman/
    Edit ~/.profile to source ~/.config/envman/load.sh
    Edit ~/.bashrc to source ~/.config/envman/load.sh
    Downloading lsd from
      https://github.com/lsd-rs/lsd/releases/download/v1.1.5/lsd-v1.1.5-x86_64-unknown-linux-musl.tar.gz
    Saved as ~/Downloads/webi/lsd/1.1.5/lsd-v1.1.5-x86_64-unknown-linux-musl.tar.gz
    Extracting ~/Downloads/webi/lsd/1.1.5/lsd-v1.1.5-x86_64-unknown-linux-musl.tar.gz
    Installing to ~/.local/opt/lsd-v1.1.5/bin/lsd

    Installed 'lsd v1.1.5' as ~/.local/bin/lsd

    Edit ~/.config/envman/PATH.env to add:
        ~/.local/bin

>>> ACTION REQUIRED <<<
        Copy, paste & run the following command:
        source ~/.config/envman/PATH.env
        (newly opened terminal windows will update automatically)

root@main:~/worldbanc/public# lsd
 company_info.md   pr_ideas.txt   products
root@main:~/worldbanc/public# cd ../private/
root@main:~/worldbanc/private# lsd --tree
 .
├──  bin
│   ├──  genids.sh
│   ├──  malicious.sh
│   ├──  process_transactions.sh
│   ├──  warn.sh
│   └──  worldbanc.sh
├──  cmd
│   ├──  genlogs
│   │   └──  main.go
│   └──  gentransactions
│       └──  main.go
├──  customers
│   └──  records.csv
├──  key.txt
├──  logs
│   ├──  2024-01-10.log
│   ├──  2024-01-11.log
│   ├──  2024-01-12.log
│   ├──  2024-01-13.log
│   ├──  2024-01-14.log
│   ├──  2024-01-15.log
│   └──  2024-01-16.log
└──  transactions
    ├──  2020.csv
    ├──  2021.csv
    ├──  2022.csv
    ├──  2023.csv
    ├── 󰁯 backups
    │   ├──  2020.csv
    │   ├──  2021.csv
    │   ├──  2022.csv
    │   └──  2023.csv
    ├──  error.txt
    ├──  error2.txt
    └──  hello.txt
root@main:~/worldbanc/private# cd transactions/
root@main:~/worldbanc/private/transactions# lsd --tree --classic
.
├── 2020.csv
├── 2021.csv
├── 2022.csv
├── 2023.csv
├── backups
│   ├── 2020.csv
│   ├── 2021.csv
│   ├── 2022.csv
│   └── 2023.csv
├── error.txt
├── error2.txt
└── hello.txt
root@main:~/worldbanc/private/transactions# lsd --tree
 .
├──  2020.csv
├──  2021.csv
├──  2022.csv
├──  2023.csv
├── 󰁯 backups
│   ├──  2020.csv
│   ├──  2021.csv
│   ├──  2022.csv
│   └──  2023.csv
├──  error.txt
├──  error2.txt
└──  hello.txt
root@main:~/worldbanc/private/transactions# exit
logout
There are stopped jobs.
root@main:~/worldbanc/private/transactions# exit
logout
Connection to 146.190.111.51 closed.

╭─ cmd     羽1h 35m 34s 527ms                                                   100   30, 15:24 
╰─>
