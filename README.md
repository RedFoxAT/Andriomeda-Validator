## _How to become a validator "Active" / Как получить статус Валидатора "Активный"_
Ваши действия для того, чтобы стать активным валидатором / Your actions to become an active validator::
1. После установки и синхронизации ноды Вам необходимо запросить тестовые токены в ```DISCORD``` - https://discord.com/channels/932744941162098688/1019632226113175552 <br>
   After installing and synchronizing the nodes, you need to request test tokens in ```DISCORD``` - https://discord.com/channels/932744941162098688/1019632226113175552 <br>
2. Узнаете Ваш адрес валидатора / Find out your address of the validator ```andromedad keys show wallet --bech val -a```
3. Делегируете токены с кошелька командой / Delegate tokens from the wallet with the command ```andromedad tx staking delegate YOUR_VALOPER_ADDRESS AMOUNTuandr --from wallet --chain-id galileo-3 --fees 5000uandr```
4. В ```EXPLORER``` - https://testnet-ping.wildsage.io/andromeda/staking смотрим стейк последнего активного валидатора / see the steak of the last active validator <img width="1409" alt="Снимок экрана 2023-03-06 в 20 08 22" src="https://user-images.githubusercontent.com/126602081/223181478-715731d9-022b-46b7-ad0a-9766ed10d948.png">
5. Для получения статуса АКТИВНЫЙ Вам необходимо увеличить свой стейк больше, чем у последнего активного на текущий момент валидатора / To become ACTIVE, you need to increase your steak more than the last currently active validator
