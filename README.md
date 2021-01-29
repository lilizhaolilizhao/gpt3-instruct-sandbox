# gpt3-instruct-sandbox
Interactive Jupyter Notebook Environment for using the GPT-3 Instruct API

# Description

This project updates an existing GPT-3 sandbox project (https://github.com/shreyashankar/gpt3-sandbox) to interact with OpenAI's Instruct API (still in beta, join waitlist at https://share.hsforms.com/1Lfc7WtPLRk2ppXhPjcYY-A4sk30).

Example includes Interactive UI using IPython Widgets to input prompt to GPT-3 and then run SQL code (using sqalchemy) in one place. 

Article describing GPT-3 Instruct usage is located at: https://blog.seekwell.io/gpt3.

解放程序员双手！GPT-3自动生成SQL语句 | 代码开源
原创量子位2021-01-28 13:16:49
金磊 发自 凹非寺 
量子位 报道 | 公众号 QbitAI
“无所不能”的GPT-3，现在又来解放程序员们的双手了。

像这样，只需用简单的英文问下GPT-3“上个月注册了多少个用户”。

GPT-3便会迅速作答，给出对应的SQL语句：

SELECT COUNT(*) FROM users
WHERE signup_time > now() - interval ‘1 month’

......
