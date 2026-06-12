

```
sudo salt '*' test.ping


sudo salt server state.apply opencode
sudo salt server state.apply opencode.user pillar='{"opencode_user":"krajak"}'
sudo salt server state.apply opencode.user pillar='{"opencode_user":"karmar"}'
sudo salt server state.apply opencode.user pillar='{"opencode_user":"waland"}'
sudo salt server state.apply opencode.upgrade

```
