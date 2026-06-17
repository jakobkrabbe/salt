

```
sudo salt '*' test.ping


sudo salt server state.apply opencode
sudo salt server state.apply opencode.user pillar='{"opencode_user":"krajak"}'
sudo salt server state.apply opencode.user pillar='{"opencode_user":"karmar"}'
sudo salt server state.apply opencode.user pillar='{"opencode_user":"waland"}'
sudo salt server state.apply opencode.update

sudo salt-call state.apply odoo.clicktest pillar='{"repo_file": "skog-test.repo"}'


```
