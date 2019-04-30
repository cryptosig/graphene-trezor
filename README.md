# graphene-trezor
Creates HD derived accounts and supplies private keys using the trezor
<p>
Required libraries: Trezor-firmware & Trezor Python; OpenSSL
<p>
Usage Examples:
graphene-trezor accountname network
<br>graphene-trezor peerplaysuser PPY
<p>
for steemit:
<br>graphene-trezor --extended steemituser STEEM (generates a set of owner,active, and memo keys)
<br>graphene-trezor -p steemituser STEEM (generates just a posting key)
<p>
for EOS:
<br>graphene-trezor eosuser EOS (give the publickeys to a service like accountcreat, https://eos-account-creator.com/)
