# NEVACOIN

addressHeader = 53;
p2shHeader = 5;
acceptableAddressCodes = new int[] { addressHeader, p2shHeader };
spendableCoinbaseDepth = 25;
dumpedPrivateKeyHeader = 177;
name = "Nevacoin";
symbol = "NEVA";
uriScheme = "nevacoin";
bip44Index = 10;
unitExponent = 8;
feeValue = value(100); // 0.000001 NEVA
minNonDust = value(1);
softDustLimit = value(1000000); // 0.01 NEVA
softDustPolicy = SoftDustPolicy.AT_LEAST_BASE_FEE_IF_SOFT_DUST_TXO_PRESENT;


# AQUARIUSCOIN

addressHeader = 23;
p2shHeader = 5;
acceptableAddressCodes = new int[] { addressHeader, p2shHeader };
spendableCoinbaseDepth = 20;
dumpedPrivateKeyHeader = 151;
name = "Aquariuscoin";
symbol = "ARCO";
uriScheme = "aquariuscoin";
bip44Index = 10;
unitExponent = 8;
feeValue = value(10000); // 0.0001 ARCO
minNonDust = value(1);
softDustLimit = value(1000000); // 0.01 ARCO
softDustPolicy = SoftDustPolicy.AT_LEAST_BASE_FEE_IF_SOFT_DUST_TXO_PRESENT;


# LANACOIN

addressHeader = 48;
p2shHeader = 5;
acceptableAddressCodes = new int[] { addressHeader, p2shHeader };
spendableCoinbaseDepth = 15;
dumpedPrivateKeyHeader = 176;
name = "Lanacoin";
symbol = "LANA";
uriScheme = "lanacoin";
bip44Index = 10;
unitExponent = 8;
feeValue = value(100); // 0.000001 LANA
minNonDust = value(1);
softDustLimit = value(1000000); // 0.01 LANA
softDustPolicy = SoftDustPolicy.AT_LEAST_BASE_FEE_IF_SOFT_DUST_TXO_PRESENT;


# TAJCOIN

addressHeader = 65;
p2shHeader = 5;
acceptableAddressCodes = new int[] { addressHeader, p2shHeader };
spendableCoinbaseDepth = 33;
dumpedPrivateKeyHeader = 111;
name = "Tajcoin";
symbol = "TAJ";
uriScheme = "tajcoin";
bip44Index = 10;
unitExponent = 8;
feeValue = value(100); // 0.000001 TAJ
minNonDust = value(1);
softDustLimit = value(1000000); // 0.01 TAJ
softDustPolicy = SoftDustPolicy.AT_LEAST_BASE_FEE_IF_SOFT_DUST_TXO_PRESENT;




