

```
sudo salt '*' test.ping


sudo salt server-test state.apply opencode
sudo salt server-test state.apply opencode.user pillar='{"opencode_user":"krajak"}'
sudo salt server-test state.apply opencode.user pillar='{"opencode_user":"karmar"}'
sudo salt server-test state.apply opencode.user pillar='{"opencode_user":"waland"}'
sudo salt server-test state.apply opencode.upgrade

```
