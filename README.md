The official Re-Branding of GPU-Coin

NulleX - $ NLX

Instructions


NulleX Win Wallet

Download & Run.  Hard-coded Nodes – It will sync on its own



Linux Daemon

git clone https://github.com/white92d15b7/GPU-Coin.git

cd GPU-Coin

cd src/leveldb

sudo make clean
sudo make libleveldb.a libmemenv.a

cd .. (you should be in GPU-Coin/src now)

sudo make -f makefile.unix (if all your deps are met this will build successfully)

strip NulleXd

sudo cp NulleXd /usr/bin

NulleXd

Either make a .conf file or download NulleX.conf place it in .NulleX



BOOTSTRAP

Due to large syncing time you may choose to use the BOOTSTRAP. 

Place bootstrap.dat into your NulleX/GPU folder and start the wallet.

The wallet may appear frozen, ITS NOT.  Be paitent.  You can verify its loading by watching the file size of blk0001.dat increasing





*** If you are running the older version of the wallet GPU, or have downloaded the current MAC/OSX/APPLE wallet you will require to download gpu.conf and place it in the working directory for staking to start.***

