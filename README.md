# BNBFlashLoan
Pinjam 100BNB, Rolling, Untung 50BNB

Okau gais, tutorial ni simple. Korang perlukan metamask wallet dan Internet. 

Apa Kita Nak Buat? 

Wujudkan 2 LiquidityPool melalui smart contract di Pancakeswap dengan melancarkan LP token Bep20 sendiri, kita namakan My Token;

Lancarkan smart-contract untuk flashloan dari Multiplier.Finance (MCL) sebanyak 100 BNB. Masuk kan dana collateral sebanyak 0.2 BNB kedalam smartcontract;

Terima flashloan Dan swap 50% dari BNB kepada DAI di Pancakeswap;

Pindahkan kesemua fund ke MyToken;

Nilai MyToken ditentukan sendiri pada anda, pada tutorial ini kita set nilai Token A (BNB) Token B (Dai);

MyToken > Token A = 1:1
MyToken > Token B = 100:1
1 MyToken = 1 BNB
1 MyToken = 100 DAI 

Ingat flashloan yang dibuat awal tadi? dari 100 BNB kita swap 50% ke DAI dan hantar fund ke LP Pancakeswap, menjadikan 50BNB + 500 DAI.

Swap semua token mengikut turutan berikut { 
50 BNB > 50 MyToken
50 MyToken > 500 DAI 
750 DAI > 150 BNB
}
100 BNB dipulangkan kembali kepada Mulplier.Finance, baki 50BNB adalah untung bersih;

