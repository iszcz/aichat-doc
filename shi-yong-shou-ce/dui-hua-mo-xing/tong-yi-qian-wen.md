# 2⃣ 通义千问

* 通义千问是阿里巴巴达摩院自主研发的超大规模语言模型，能够在用户自然语言输入的基础上，通过自然语言理解和语义分析，在不同领域、任务内为用户提供服务和帮助。
* 模型具备的能力包括但不限于：

1. 创作文字，如写故事、写公文、写邮件、写剧本、写诗歌等
2. 编写代码
3. 提供各类语言的翻译服务，如英语、日语、法语、西班牙语等
4. 进行文本润色和文本摘要等工作
5. 扮演角色进行对话
6. 制作图表

> 通义千问以用户以文本形式输入的指令（prompt）以及不定轮次的对话历史（history）作为输入，返回模型生成的回复作为输出。在这一过程中，文本将被转换为语言模型可以处理的token序列。Token是模型用来表示自然语言文本的基本单位，可以直观的理解为“字”或“词”。对于中文文本来说，1个token通常对应一个汉字；对于英文文本来说，1个token通常对应3至4个字母或1个单词。例如，中文文本“你好，我是通义千问”会被转换成序列\['你', '好', '，', '我', '是', '通', '义', '千', '问']，而英文文本"Nice to meet you."则会被转换成\['Nice', ' to', ' meet', ' you', '.']。

\
