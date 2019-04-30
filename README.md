# graphene-trezor
Creates HD derived accounts and supplies private keys using the trezor

Required libraries: Trezor-firmware & Trezor Python; OpenSSL

Usage Examples:
graphene-trezor accountname network

graphene-trezor peerplaysuser PPY

for steemit:
graphene-trezor --extended steemituser STEEM (generates a set of owner,active, and memo keys)
graphene-trezor -p steemituser STEEM (generates just a posting key)

for EOS:
graphene-trezor eosuser EOS (give the publickeys to a service like accountcreat, https://eos-account-creator.com/)
