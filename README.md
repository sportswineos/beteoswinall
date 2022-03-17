# beteoswinall
Bet by transferring EOS to account 'beteoswinall' with memo. <br>
Memo consist of two parts splitted by '-', the first part is id of the game and the second part is your bet side. <br>
Home team name with '+' or '-' follow by number is handicapping and rate(win, draw, lost) is dynamic.<br>
Rejected bet will be refunded and column hash is empty. <br>
Explore onchain contract data for lastest game detail. <br>
For example visit https://www.eosx.io/account/beteoswinall?mode=contract&sub=tables&table=matchtable or https://www.bloks.io/account/beteoswinall?loadContract=true&tab=Tables&table=matchtable for detail.<br>
<br>

下注仅需转账给 beteoswinall 时在备注填入场次id与下注方向(胜3平1负0)，如备注28-3为买场次28主场胜。<br>
表内数据主队名称后带+-符号代表让球数，如主队+2，比赛结果为1:3时，则买平的获胜。赔率(win, draw, lost)是定时动态更新的。<br>
未成功收单的下注hash字段为空且会提前退款。<br>
最新的场次与赔率通过查看链上合约数据获取。<br>
如访问 https://www.eosx.io/account/beteoswinall?mode=contract&sub=tables&table=matchtable 或者 https://www.bloks.io/account/beteoswinall?loadContract=true&tab=Tables&table=matchtable 。<br>
