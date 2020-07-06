# 北航计算机学院复试上机往年试题及解答（15年-至今）
## 序前の序
<br>具体的代码以文档为准，cpp文件不确保有微小的修改。希望大家能共同维护好这份文档。如有任何疑问、建议、想法和管理此Repo意愿，欢迎给我发邮件：gt3115a@163.com
<br>                                                        By 慕弋云子 2020/7/6
## 序
<br>&emsp;&emsp;因为笔者目前搜集到的资料（主要是王道论坛几位学长的帖子，红果研、400+的复试资料和各种群文件）中，在历年机试真题这部分整合得普遍都比较难受，要么是叙述不够完善，缺少各种题目需考虑的细节，要么是没有测试用例（在这里感谢阿奇大佬的资料提供了大量的测试用例），以及大部分代码缺少解释、可读性较差、方法过于繁琐。不过还是很感谢这些学长学姐提供了非常宝贵的真题回忆！
<br>&emsp;&emsp;所以笔者打算在此基础上，尽量地完善题目，对叙述不足的按个人理解补足（大部分都比较完整，并且补充的地方和原题目不会有太差的差别，核心思想不会变），并提供一定的测试用例，形成一道可以掐时间完成的、高度还原真题的试题。
<br>&emsp;&emsp;北航机试时间是两小时，根据往年学长的经验，一般会提供2~3个测试用例。所以我在题目中也会给出2~3个很基本的测试用例，并在解析和代码之后给出自测分数用的一些测试用例（主要是边界条件、特殊情况等），建议完整地做完题目后再使用自测用例核算分数。由于这部分用例需要用心设计，所以并不一定能做到全面地覆盖，大家做参考即可。
<br>&emsp;&emsp;分数是由机器评判和人工查阅的两部分综合而成，一般来讲应该是对一部分测试用例给一部分分数，而人工查阅也有分数意味着，只要代码思想表达出来了，大概框架也出来了，哪怕测试没有通过，也还是能捞到不少分数的。所以大家在估分的时候，可以参考这些规则综合评估自己的机试分数。
<br>&emsp;&emsp;此外，对每道题目也会做一定的题目解析和参考代码，这些代码都是优化过后的，所以大家如果掐时间做题或在考场上，不必太过追求代码的完美，达到要求拿分了才是最关键的，不过平时练习的时候可以根据这些参考代码进行优化。如果做起来时间相对充裕的话，也建议养成写注释的习惯，一是可以很好地梳理自己的思路（类似于先写伪代码），二是也便于给人工查阅一个很好的体验（肯定是有用的，实在没时间至少在开头写一下大思想，比如Dijkstra、DFS什么的）。
<br>&emsp;&emsp;所有代码都是针对单点测试的方式编写的，即每一个测试用例是一个文件，多次输入。当然了多点测试是最稳妥的方式，如果你习惯了多点测试的方式，用于单点肯定也是不会错的。在这一问题上大家可以根据自己的喜好自主选择，不过必须至少知道多点测试是怎么回事儿，因为15年是曾考察过多点输入的。
<br>&emsp;&emsp;水印什么的我不打算加，感觉很影响阅读体验，反正这份文档是免费开源的，我欢迎各考研机构对此不遗余力的宣传（笑）。我是真的希望这个文件能传承下去，每年都有人来维护（希望每年能有人加上自己年份的机试试题并四处上传吧），不断地加入更多测试用例或题目方法，形成一个良好的氛围，真正造福更多想花时间准备、肯下功夫的人，也算是为提升北航计算机整体质量做一些绵薄的贡献了。
<br>&emsp;&emsp;由于20年最终并未机试，以及笔者时间和水平有限，所以最终只写到了15年的，并且难免会有一些疏漏。望各位勤加批判，并对本文档做出相应的修正，共同完善好这份我们北航人的机试指南。
<br>&emsp;&emsp;如果对本文内容有任何疑问，或需补充测试用例，欢迎在本文对应的GitHub Repository中Issues中做补充。对于新试题的添加，欢迎自行添加后并广泛扩散，或直接发邮件给我：gt3115a@163.com，我会替为上传到GitHub中。如有愿意帮助管理这个Repo的同学也欢迎私信邮箱。

By 慕弋云子
2020/4/17
