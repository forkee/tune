Tune Core 
===============================

TUNE is experimental cryptocurrency for incubating and investing new cryptocurrency.
TUNE have three main features…
1st : Variable Masternode Price
2nd : Profit Sharing (Weekly, Bitcoin base)
3rd : Transparent Funding Operation (All address will be opend (include BTC wallet))
And one more thing… We will announce all progress not only roadmap but also weekly plan and result.

       
Name of Coin : TUNE
Tiker : TUN
PoW Algorithem : neoscrypt
Block Time : 90 sec (960 Block per day)
Masternode Reward : 50% ( 5 per Block, From 3840 Block)
Profit Share : 30% of Weekly Income from TUNE fund will be distributed to Registered Masternode Holder

[POW Reward]
  1) 1 per Blcok (~ 3k Block, for slow start, beta test)
  2) 10 per Block (From 3k Block ~)
  3) 5 per Block after Masternodes Run.
[Masternode Price]
  1) 1000 TUN ( 0 ~ 10,000 Block)
  2) 1500 TUN ( 10,001 ~ 20,000 Block)
  3) Every 10k Block, Masternode Price will rise 500 TUN
[Premine]
  Total 300,000 (about 30 days reward of POW)
  1) 5,000 : to the dev team. masternode test and incentive
  2) 295,000 : to the TUNE fund

----------------------------------------
Compiling Guide
----------------------------------------

1) Basic requirement (on linux)

sudo apt-get install -y curl g++ git-core pkg-config autoconf libtool automake faketime bsdmainutils mingw-w64 g++-mingw-w64 nsis zip ca-certificates python 

2) For linux (on linux)

Just copy below and paste it your linux terminal.

echo "cd depends" > run.sh

echo "sudo make -j4 HOST=x86_64-pc-linux-gnu" >> run.sh

echo "cd .." >> run.sh

echo "sudo ./autogen.sh" >> run.sh

echo "sudo ./configure --prefix=\`pwd\`/depends/x86_64-pc-linux-gnu" >> run.sh

echo "sudo make -j4" >> run.sh

sudo chmod +x run.sh

sudo ./run.sh > log


3) For windows 32bit (on linux)

Just copy below and paste it your linux terminal.

echo "cd depends" > run.sh

echo "sudo make -j4 HOST=i686-w64-mingw32" >> run.sh

echo "cd .." >> run.sh

echo "sudo ./autogen.sh" >> run.sh

echo "sudo ./configure --prefix=\`pwd\`/depends/i686-w64-mingw32" >> run.sh

echo "sudo make -j4" >> run.sh

sudo chmod +x run.sh

sudo ./run.sh > log


4) For windows 64bit (on linux)

Just copy below and paste it your linux terminal.

echo "cd depends" > run.sh

echo "sudo make -j4 HOST=x86_64-w64-mingw32" >> run.sh

echo "cd .." >> run.sh

echo "sudo ./autogen.sh" >> run.sh

echo "sudo ./configure --prefix=\`pwd\`/depends/x86_64-w64-mingw32" >> run.sh

echo "sudo make -j4" >> run.sh

sudo chmod +x run.sh

sudo ./run.sh > log

