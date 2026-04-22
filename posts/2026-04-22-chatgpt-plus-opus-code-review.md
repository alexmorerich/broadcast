# ChatGPT is not useless, it is a strong code reviewer
# ChatGPT并不是一无是处，它很适合做代码审查

## English

A lot of people treat model comparison like a winner-takes-all game.

They see Opus write stronger code and jump to the conclusion that ChatGPT is no longer useful. I do not think that is true.

Opus is often very good at writing code, but it still produces bugs. Sometimes obvious ones, sometimes subtle ones. That is exactly where ChatGPT becomes valuable.

What ChatGPT is good at in this workflow is not necessarily replacing the main coding model. It is acting like a second pair of eyes.

You can hand the result to ChatGPT and let it go into review mode:
- pull the logic apart
- nitpick the weak spots
- reconstruct the bug pattern from scattered clues
- turn messy failure symptoms into a concrete bug list

It is a bit like solving a jigsaw puzzle from pieces. One model writes. The other inspects, challenges, and pressure-tests.

Once the bug list is clear and well argued, the main coding model can stop guessing and start fixing things one by one.

That combination works surprisingly well:
- Opus for primary implementation
- ChatGPT for code review and bug finding

Used this way, the pair can produce scripts and programs with fewer bugs than either workflow alone.

The mistake is thinking every model needs to be the best at the same thing.

Sometimes the highest-leverage setup is not one model replacing another. It is one model writing, and another model exposing what the first one missed.

## 中文

很多人一谈模型对比，就喜欢用赢家通吃的思路去看。

看到 Opus 写代码更强，就很容易下结论说 ChatGPT 已经没什么用了。我不这么看。

Opus 写代码确实经常很强，但它也还是会出 bug。有些 bug 很明显，有些 bug 很隐蔽。而 ChatGPT 的价值，恰恰就在这里。

在这个工作流里，ChatGPT 最适合做的，不一定是取代主力写代码的模型，而是充当第二双眼睛。

你可以把写出来的结果交给 ChatGPT，让它进入 code review 模式：
- 拆逻辑
- 挑毛病
- 从零散线索里反推 bug 模式
- 把混乱的报错和现象整理成一份具体的 bug 清单

这个过程有点像把散落的拼图一块一块拼起来。一个模型负责写，另一个模型负责检查、质疑和压力测试。

当 bug 清单足够清楚，而且条理分明之后，主力编码模型就不用再猜了，而是可以老老实实地一个一个去修。

这种组合其实很好用：
- Opus 负责主写
- ChatGPT 负责 code review 和找 bug

这样配合下来，往往能比单独依赖任何一个工作流，写出 bug 更少的脚本和程序。

很多人的误区，是总觉得每个模型都必须在同一件事上争第一。

但很多时候，真正高杠杆的用法，不是一个模型替代另一个模型，而是一个模型负责写，另一个模型把它遗漏的问题揪出来。
